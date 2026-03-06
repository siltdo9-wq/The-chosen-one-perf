<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Chosen One Perf - Coaching privé de boxe anglaise. Ta progression, notre mission. Réservez votre séance dès maintenant.">
    <title>Chosen One Perf - Coaching Privé Boxe Anglaise</title>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;500;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-dark: #0a0e1a;
            --secondary-dark: #1a1f2e;
            --accent-blue: #3b82f6;
            --accent-cyan: #06b6d4;
            --text-light: #f8fafc;
            --text-gray: #94a3b8;
            --error-red: #f87171;
            --gradient-1: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            --gradient-2: linear-gradient(135deg, #3b82f6 0%, #06b6d4 100%);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: var(--primary-dark);
            color: var(--text-light);
            overflow-x: hidden;
            line-height: 1.6;
        }

        /* Skip to content link for accessibility */
        .skip-link {
            position: absolute;
            top: -40px;
            left: 0;
            background: var(--accent-cyan);
            color: var(--primary-dark);
            padding: 8px;
            text-decoration: none;
            z-index: 100;
            font-weight: 600;
        }

        .skip-link:focus {
            top: 0;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 1.5rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            background: rgba(10, 14, 26, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .logo {
            font-family: 'Oswald', sans-serif;
            font-size: 1.8rem;
            font-weight: 700;
            background: var(--gradient-2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-decoration: none;
        }

        .nav-links {
            display: flex;
            gap: 2.5rem;
            list-style: none;
        }

        .nav-links a {
            color: var(--text-light);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            position: relative;
            padding: 0.5rem 0;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent-cyan);
            transition: width 0.3s;
        }

        .nav-links a:hover::after,
        .nav-links a:focus::after {
            width: 100%;
        }

        .nav-links a:hover,
        .nav-links a:focus {
            color: var(--accent-cyan);
            outline: none;
        }

        /* Burger menu */
        .burger {
            display: none;
            flex-direction: column;
            gap: 5px;
            cursor: pointer;
            padding: 8px;
            background: none;
            border: 2px solid transparent;
            border-radius: 4px;
            transition: border-color 0.3s;
        }

        .burger:hover,
        .burger:focus {
            border-color: var(--accent-cyan);
            outline: none;
        }

        .burger span {
            display: block;
            width: 25px;
            height: 3px;
            background: var(--text-light);
            border-radius: 2px;
            transition: all 0.3s;
        }

        .burger.open span:nth-child(1) {
            transform: translateY(8px) rotate(45deg);
        }

        .burger.open span:nth-child(2) {
            opacity: 0;
        }

        .burger.open span:nth-child(3) {
            transform: translateY(-8px) rotate(-45deg);
        }

        .mobile-menu {
            display: none;
            position: fixed;
            top: 73px;
            left: 0;
            width: 100%;
            background: rgba(10, 14, 26, 0.98);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255,255,255,0.1);
            z-index: 999;
            padding: 1.5rem 5%;
            flex-direction: column;
            gap: 0;
        }

        .mobile-menu.open {
            display: flex;
        }

        .mobile-menu a {
            color: var(--text-light);
            text-decoration: none;
            font-weight: 500;
            font-size: 1.1rem;
            padding: 1rem 0;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            transition: color 0.3s, padding-left 0.3s;
        }

        .mobile-menu a:last-child {
            border-bottom: none;
        }

        .mobile-menu a:hover,
        .mobile-menu a:focus {
            color: var(--accent-cyan);
            padding-left: 1rem;
            outline: none;
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            background: var(--gradient-1);
            overflow: hidden;
            padding: 2rem;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                radial-gradient(circle at 20% 50%, rgba(59, 130, 246, 0.15) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(6, 182, 212, 0.1) 0%, transparent 50%);
            pointer-events: none;
        }

        .hero-content {
            text-align: center;
            z-index: 2;
            max-width: 900px;
            animation: fadeInUp 0.8s ease;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .hero-badge {
            display: inline-block;
            padding: 0.5rem 1.5rem;
            background: rgba(59, 130, 246, 0.2);
            border: 1px solid var(--accent-blue);
            border-radius: 50px;
            font-size: 0.9rem;
            color: var(--accent-cyan);
            margin-bottom: 2rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: 500;
        }

        .hero h1 {
            font-family: 'Oswald', sans-serif;
            font-size: clamp(2.5rem, 8vw, 6rem);
            font-weight: 700;
            line-height: 1.1;
            margin-bottom: 1.5rem;
            text-transform: uppercase;
        }

        .hero h1 span {
            background: var(--gradient-2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .slogan {
            font-size: clamp(1.2rem, 3vw, 1.8rem);
            color: var(--text-gray);
            margin-bottom: 3rem;
            font-style: italic;
            position: relative;
            display: inline-block;
            padding: 0 2rem;
        }

        .slogan::before,
        .slogan::after {
            content: '';
            position: absolute;
            top: 50%;
            width: 40px;
            height: 2px;
            background: var(--accent-cyan);
        }

        .slogan::before {
            right: calc(100% - 10px);
        }

        .slogan::after {
            left: calc(100% - 10px);
        }

        .cta-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 1rem 2.5rem;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            font-family: 'Inter', sans-serif;
        }

        .btn:focus {
            outline: 3px solid var(--accent-cyan);
            outline-offset: 2px;
        }

        .btn-primary {
            background: var(--gradient-2);
            color: white;
            box-shadow: 0 10px 30px rgba(59, 130, 246, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(59, 130, 246, 0.4);
        }

        .btn-secondary {
            background: transparent;
            color: var(--text-light);
            border: 2px solid rgba(255,255,255,0.3);
        }

        .btn-secondary:hover {
            border-color: var(--accent-cyan);
            color: var(--accent-cyan);
            transform: translateY(-3px);
        }

        /* Coach Section */
        .coach-section {
            padding: 6rem 5%;
            background: var(--secondary-dark);
        }

        .section-container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }

        .coach-image {
            position: relative;
        }

        .coach-image img {
            width: 100%;
            height: auto;
            border-radius: 20px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
            border: 2px solid rgba(59, 130, 246, 0.3);
            display: block;
        }

        .coach-image::before {
            content: '';
            position: absolute;
            top: -20px;
            left: -20px;
            right: 20px;
            bottom: 20px;
            border: 2px solid var(--accent-cyan);
            border-radius: 20px;
            z-index: -1;
            opacity: 0.5;
        }

        .coach-content h2 {
            font-family: 'Oswald', sans-serif;
            font-size: clamp(2rem, 5vw, 3rem);
            margin-bottom: 1.5rem;
            text-transform: uppercase;
        }

        .coach-content h2 span {
            color: var(--accent-cyan);
        }

        .coach-content p {
            color: var(--text-gray);
            line-height: 1.8;
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .stat-item {
            text-align: center;
            padding: 1.5rem 1rem;
            background: rgba(255,255,255,0.05);
            border-radius: 12px;
            border: 1px solid rgba(255,255,255,0.1);
            transition: transform 0.3s;
        }

        .stat-item:hover {
            transform: translateY(-5px);
            border-color: var(--accent-blue);
        }

        .stat-number {
            font-family: 'Oswald', sans-serif;
            font-size: 2rem;
            color: var(--accent-cyan);
            font-weight: 700;
        }

        .stat-label {
            color: var(--text-gray);
            font-size: 0.85rem;
            margin-top: 0.5rem;
        }

        /* Services Section */
        .services {
            padding: 6rem 5%;
            background: var(--primary-dark);
        }

        .section-header {
            text-align: center;
            margin-bottom: 4rem;
        }

        .section-header h2 {
            font-family: 'Oswald', sans-serif;
            font-size: clamp(2rem, 5vw, 3rem);
            text-transform: uppercase;
            margin-bottom: 1rem;
        }

        .section-header p {
            color: var(--text-gray);
            font-size: 1.2rem;
        }

        .services-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: var(--secondary-dark);
            padding: 2.5rem;
            border-radius: 16px;
            border: 1px solid rgba(255,255,255,0.1);
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }

        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: var(--gradient-2);
            transform: scaleX(0);
            transition: transform 0.3s;
        }

        .service-card:hover::before,
        .service-card:focus-within::before {
            transform: scaleX(1);
        }

        .service-card:hover,
        .service-card:focus-within {
            transform: translateY(-10px);
            border-color: var(--accent-blue);
            box-shadow: 0 20px 40px rgba(59, 130, 246, 0.2);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background: var(--gradient-2);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
        }

        .service-card h3 {
            font-family: 'Oswald', sans-serif;
            font-size: 1.3rem;
            margin-bottom: 1rem;
            text-transform: uppercase;
        }

        .service-card p {
            color: var(--text-gray);
            line-height: 1.6;
        }

        /* Pricing Section */
        .pricing {
            padding: 6rem 5%;
            background: var(--secondary-dark);
        }

        .pricing-grid {
            max-width: 1000px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .pricing-card {
            background: var(--primary-dark);
            padding: 2.5rem 2rem;
            border-radius: 16px;
            border: 2px solid rgba(255,255,255,0.1);
            text-align: center;
            transition: all 0.3s;
            position: relative;
            display: flex;
            flex-direction: column;
        }

        .pricing-card.featured {
            border-color: var(--accent-blue);
            transform: scale(1.02);
            box-shadow: 0 20px 40px rgba(59, 130, 246, 0.3);
        }

        .pricing-card.featured::before {
            content: 'POPULAIRE';
            position: absolute;
            top: -12px;
            left: 50%;
            transform: translateX(-50%);
            background: var(--gradient-2);
            padding: 0.4rem 1.2rem;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 1px;
            white-space: nowrap;
        }

        .pricing-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-cyan);
        }

        .pricing-card.featured:hover {
            transform: scale(1.02) translateY(-5px);
        }

        .pricing-name {
            font-family: 'Oswald', sans-serif;
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            text-transform: uppercase;
            color: var(--text-gray);
        }

        .pricing-price {
            font-family: 'Oswald', sans-serif;
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }

        .pricing-price span {
            font-size: 0.9rem;
            color: var(--text-gray);
            font-weight: 400;
        }

        .pricing-features {
            list-style: none;
            margin: 1.5rem 0;
            text-align: left;
            flex-grow: 1;
        }

        .pricing-features li {
            padding: 0.5rem 0;
            color: var(--text-gray);
            border-bottom: 1px solid rgba(255,255,255,0.05);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .pricing-features li::before {
            content: '✓';
            color: var(--accent-cyan);
            font-weight: bold;
        }

        .pricing-features li:last-child {
            border-bottom: none;
        }

        /* Booking Section */
        .booking {
            padding: 6rem 5%;
            background: var(--primary-dark);
        }

        .booking-container {
            max-width: 700px;
            margin: 0 auto;
            background: var(--secondary-dark);
            padding: 2.5rem;
            border-radius: 24px;
            border: 1px solid rgba(255,255,255,0.1);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: var(--text-light);
            font-weight: 500;
            font-size: 0.95rem;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 0.9rem 1rem;
            background: var(--primary-dark);
            border: 2px solid rgba(255,255,255,0.1);
            border-radius: 8px;
            color: var(--text-light);
            font-size: 1rem;
            font-family: 'Inter', sans-serif;
            transition: all 0.3s;
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: var(--accent-blue);
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.1);
        }

        .form-group input:invalid:not(:placeholder-shown),
        .form-group select:invalid:not(:placeholder-shown) {
            border-color: var(--error-red);
        }

        .form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.5rem;
        }

        .date-time-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 0.75rem;
            margin-top: 0.5rem;
        }

        .time-slot {
            padding: 0.7rem 0.5rem;
            background: var(--primary-dark);
            border: 2px solid rgba(255,255,255,0.1);
            border-radius: 8px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 0.9rem;
            user-select: none;
            font-family: 'Inter', sans-serif;
        }

        .time-slot:hover:not(.disabled) {
            border-color: var(--accent-blue);
            background: rgba(59, 130, 246, 0.1);
        }

        .time-slot:focus {
            outline: 2px solid var(--accent-cyan);
            outline-offset: 2px;
        }

        .time-slot.selected {
            background: var(--gradient-2);
            border-color: var(--accent-cyan);
            color: white;
            font-weight: 600;
        }

        .time-slot.disabled {
            opacity: 0.3;
            cursor: not-allowed;
            text-decoration: line-through;
        }

        .time-error {
            display: none;
            color: var(--error-red);
            font-size: 0.85rem;
            margin-top: 0.5rem;
            align-items: center;
            gap: 0.3rem;
        }

        .time-error::before {
            content: '⚠';
        }

        .time-error.visible {
            display: flex;
        }

        .submit-btn {
            width: 100%;
            padding: 1.1rem;
            background: var(--gradient-2);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 1rem;
            font-family: 'Inter', sans-serif;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
        }

        .submit-btn:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(59, 130, 246, 0.4);
        }

        .submit-btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }

        /* Modal */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.85);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(5px);
            padding: 1rem;
        }

        .modal.active {
            display: flex;
        }

        .modal-content {
            background: var(--secondary-dark);
            padding: 2.5rem;
            border-radius: 20px;
            text-align: center;
            max-width: 400px;
            width: 100%;
            border: 2px solid var(--accent-cyan);
            animation: modalPop 0.3s ease;
            position: relative;
        }

        @keyframes modalPop {
            0% { transform: scale(0.9); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        .modal-icon {
            width: 70px;
            height: 70px;
            background: var(--gradient-2);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            margin: 0 auto 1.5rem;
        }

        .modal h3 {
            font-family: 'Oswald', sans-serif;
            font-size: 1.6rem;
            margin-bottom: 1rem;
        }

        .modal p {
            color: var(--text-gray);
            margin-bottom: 2rem;
            line-height: 1.6;
        }

        /* Footer */
        footer {
            background: var(--primary-dark);
            padding: 3rem 5%;
            text-align: center;
            border-top: 1px solid rgba(255,255,255,0.1);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .social-links a {
            width: 50px;
            height: 50px;
            background: var(--secondary-dark);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-light);
            text-decoration: none;
            transition: all 0.3s;
            border: 1px solid rgba(255,255,255,0.1);
        }

        .social-links a:hover,
        .social-links a:focus {
            background: var(--gradient-2);
            transform: translateY(-5px);
            border-color: var(--accent-cyan);
            outline: none;
        }

        .footer-text {
            color: var(--text-gray);
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }

        .instagram-handle {
            color: var(--accent-cyan);
            font-weight: 600;
            font-size: 1.1rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .burger {
                display: flex;
            }

            .section-container {
                grid-template-columns: 1fr;
                gap: 3rem;
            }

            .coach-image::before {
                display: none;
            }

            .stats {
                grid-template-columns: 1fr;
            }

            .form-row {
                grid-template-columns: 1fr;
                gap: 1rem;
            }

            .date-time-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .pricing-card.featured {
                transform: none;
            }

            .pricing-card.featured:hover {
                transform: translateY(-5px);
            }

            .slogan::before,
            .slogan::after {
                display: none;
            }

            .booking-container {
                padding: 1.5rem;
            }
        }

        @media (max-width: 480px) {
            .hero {
                padding: 1rem;
            }

            .date-time-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 0.5rem;
            }

            .time-slot {
                font-size: 0.85rem;
                padding: 0.6rem 0.3rem;
            }
        }

        /* Animations */
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Loading Spinner */
        .spinner {
            display: none;
            width: 20px;
            height: 20px;
            border: 3px solid rgba(255,255,255,0.3);
            border-radius: 50%;
            border-top-color: white;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        .submit-btn.loading .spinner {
            display: block;
        }

        .submit-btn.loading .btn-text {
            opacity: 0.8;
        }

        /* Reduced motion */
        @media (prefers-reduced-motion: reduce) {
            *,
            *::before,
            *::after {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
            }
            
            html {
                scroll-behavior: auto;
            }
        }
    </style>
</head>
<body>
    <a href="#main-content" class="skip-link">Aller au contenu principal</a>

    <!-- Navigation -->
    <nav role="navigation" aria-label="Navigation principale">
        <a href="#accueil" class="logo">Chosen One Perf</a>
        <ul class="nav-links" role="menubar">
            <li role="none"><a href="#accueil" role="menuitem">Accueil</a></li>
            <li role="none"><a href="#coach" role="menuitem">Le Coach</a></li>
            <li role="none"><a href="#services" role="menuitem">Services</a></li>
            <li role="none"><a href="#tarifs" role="menuitem">Tarifs</a></li>
            <li role="none"><a href="#reservation" class="btn-primary" style="padding: 0.5rem 1.5rem; font-size: 0.9rem;" role="menuitem">Réserver</a></li>
        </ul>
        <button class="burger" id="burgerBtn" aria-label="Ouvrir le menu" aria-expanded="false" aria-controls="mobileMenu">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
        </button>
    </nav>

    <div class="mobile-menu" id="mobileMenu" role="navigation" aria-label="Menu mobile">
        <a href="#accueil" onclick="closeMobileMenu()">Accueil</a>
        <a href="#coach" onclick="closeMobileMenu()">Le Coach</a>
        <a href="#services" onclick="closeMobileMenu()">Services</a>
        <a href="#tarifs" onclick="closeMobileMenu()">Tarifs</a>
        <a href="#reservation" onclick="closeMobileMenu()">Réserver</a>
    </div>

    <main id="main-content">
        <!-- Hero Section -->
        <section class="hero" id="accueil" aria-labelledby="hero-title">
            <div class="hero-content">
                <div class="hero-badge">@chosenoneperf</div>
                <h1 id="hero-title">Coaching <span>Privé</span></h1>
                <p class="slogan" role="doc-subtitle">Ta progression, notre mission.</p>
                <div class="cta-buttons">
                    <button class="btn btn-primary" onclick="scrollToBooking()">Réserver une séance</button>
                    <a href="#coach" class="btn btn-secondary">Découvrir</a>
                </div>
            </div>
        </section>

        <!-- Coach Section -->
        <section class="coach-section" id="coach" aria-labelledby="coach-title">
            <div class="section-container">
                <div class="coach-image fade-in">
                    <img src="https://images.unsplash.com/photo-1549719386-74dfcbf7dbed?w=800&q=80" alt="Coach de boxe anglaise en position de garde, prêt à donner un cours" loading="lazy" width="600" height="400">
                </div>
                <div class="coach-content fade-in">
                    <h2 id="coach-title">Votre <span>Coach</span></h2>
                    <p>Passionné de boxe anglaise depuis plus de 10 ans, je mets mon expertise au service de votre progression. Que vous soyez débutant ou confirmé, chaque séance est adaptée à vos objectifs et votre niveau.</p>
                    <p>Ma méthode allie technique, condition physique et mental de fer. Parce que la boxe n'est pas qu'un sport, c'est un mode de vie.</p>
                    <div class="stats">
                        <div class="stat-item">
                            <div class="stat-number" aria-label="10 années d'expérience">10+</div>
                            <div class="stat-label">Années d'exp.</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" aria-label="500 boxeurs coachés">500+</div>
                            <div class="stat-label">Boxeurs coachés</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" aria-label="100 pourcent de passion">100%</div>
                            <div class="stat-label">Passion</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section class="services" id="services" aria-labelledby="services-title">
            <div class="section-header fade-in">
                <h2 id="services-title">Nos Services</h2>
                <p>Des programmes adaptés à tous les niveaux</p>
            </div>
            <div class="services-grid">
                <article class="service-card fade-in" tabindex="0">
                    <div class="service-icon" aria-hidden="true">🥊</div>
                    <h3>Remise en forme</h3>
                    <p>Programme complet alliant cardio et musculation pour retrouver la forme physique et mentale.</p>
                </article>
                <article class="service-card fade-in" tabindex="0">
                    <div class="service-icon" aria-hidden="true">🎯</div>
                    <h3>Initiation à la boxe</h3>
                    <p>Apprenez les bases de la boxe anglaise : garde, déplacements, coups de poing et défense.</p>
                </article>
                <article class="service-card fade-in" tabindex="0">
                    <div class="service-icon" aria-hidden="true">⚡</div>
                    <h3>Perfectionnement technique</h3>
                    <p>Affinez votre technique, travaillez vos combos et devenez plus efficace sur le ring.</p>
                </article>
                <article class="service-card fade-in" tabindex="0">
                    <div class="service-icon" aria-hidden="true">🔥</div>
                    <h3>Perte de poids</h3>
                    <p>Sessions intensives pour brûler des calories et atteindre vos objectifs de poids.</p>
                </article>
            </div>
        </section>

        <!-- Pricing Section -->
        <section class="pricing" id="tarifs" aria-labelledby="pricing-title">
            <div class="section-header fade-in">
                <h2 id="pricing-title">Nos Tarifs</h2>
                <p>Choisissez la formule qui vous convient</p>
            </div>
            <div class="pricing-grid">
                <article class="pricing-card fade-in">
                    <div class="pricing-name">Solo</div>
                    <div class="pricing-price">20€<span>/séance</span></div>
                    <ul class="pricing-features">
                        <li>Séance individuelle 1h</li>
                        <li>Programme personnalisé</li>
                        <li>Conseils nutritionnels</li>
                    </ul>
                    <button class="btn btn-secondary" onclick="selectPack('solo')" style="width: 100%; margin-top: auto;">Choisir</button>
                </article>
                <article class="pricing-card featured fade-in">
                    <div class="pricing-name">Duo</div>
                    <div class="pricing-price">15€<span>/pers</span></div>
                    <ul class="pricing-features">
                        <li>Séance en binôme 1h</li>
                        <li>Motivation partagée</li>
                        <li>Exercices sparring léger</li>
                    </ul>
                    <button class="btn btn-primary" onclick="selectPack('duo')" style="width: 100%; margin-top: auto;">Choisir</button>
                </article>
                <article class="pricing-card fade-in">
                    <div class="pricing-name">Groupe</div>
                    <div class="pricing-price">10€<span>/pers</span></div>
                    <ul class="pricing-features">
                        <li>Jusqu'à 4 personnes</li>
                        <li>Ambiance dynamique</li>
                        <li>Circuit training</li>
                    </ul>
                    <button class="btn btn-secondary" onclick="selectPack('groupe')" style="width: 100%; margin-top: auto;">Choisir</button>
                </article>
            </div>
            <div style="max-width: 800px; margin: 0 auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem;">
                <article class="pricing-card fade-in">
                    <div class="pricing-name">Pack 5 Séances</div>
                    <div class="pricing-price">95€</div>
                    <ul class="pricing-features">
                        <li>5 séances individuelles</li>
                        <li>Économisez 5€</li>
                        <li>Validité 2 mois</li>
                    </ul>
                    <button class="btn btn-secondary" onclick="selectPack('pack5')" style="width: 100%; margin-top: auto;">Choisir</button>
                </article>
                <article class="pricing-card fade-in">
                    <div class="pricing-name">Pack 10 Séances</div>
                    <div class="pricing-price">180€</div>
                    <ul class="pricing-features">
                        <li>10 séances individuelles</li>
                        <li>Économisez 20€</li>
                        <li>Validité 3 mois</li>
                    </ul>
                    <button class="btn btn-secondary" onclick="selectPack('pack10')" style="width: 100%; margin-top: auto;">Choisir</button>
                </article>
            </div>
        </section>

        <!-- Booking Section -->
        <section class="booking" id="reservation" aria-labelledby="booking-title">
            <div class="section-header fade-in">
                <h2 id="booking-title">Réserver votre séance</h2>
                <p>Prise de rendez-vous en privé</p>
            </div>
            <div class="booking-container fade-in">
                <form id="bookingForm" novalidate>
                    <div class="form-row">
                        <div class="form-group">
                            <label for="prenom">Prénom *</label>
                            <input type="text" id="prenom" name="prenom" required autocomplete="given-name" placeholder="Jean">
                        </div>
                        <div class="form-group">
                            <label for="nom">Nom *</label>
                            <input type="text" id="nom" name="nom" required autocomplete="family-name" placeholder="Dupont">
                        </div>
                    </div>

                    <div class="form-row">
                        <div class="form-group">
                            <label for="email">Email *</label>
                            <input type="email" id="email" name="email" required autocomplete="email" placeholder="jean.dupont@email.com">
                        </div>
                        <div class="form-group">
                            <label for="telephone">Téléphone *</label>
                            <input type="tel" id="telephone" name="telephone" required autocomplete="tel" placeholder="06 12 34 56 78" pattern="[0-9]{10}" title="10 chiffres sans espaces">
                        </div>
                    </div>

                    <div class="form-group">
                        <label for="pack">Formule choisie *</label>
                        <select id="pack" name="pack" required>
                            <option value="" disabled selected>Sélectionnez une formule</option>
                            <option value="solo">Solo - 20€/séance</option>
                            <option value="duo">Duo - 15€/personne</option>
                            <option value="groupe">Groupe - 10€/personne</option>
                            <option value="pack5">Pack 5 séances - 95€</option>
                            <option value="pack10">Pack 10 séances - 180€</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label for="date">Date souhaitée *</label>
                        <input type="date" id="date" name="date" required min="">
                    </div>

                    <div class="form-group">
                        <label id="time-label">Créneau horaire *</label>
                        <div class="date-time-grid" id="timeSlots" role="radiogroup" aria-labelledby="time-label">
                            <button type="button" class="time-slot" data-time="09:00" role="radio" aria-checked="false" tabindex="0">09:00</button>
                            <button type="button" class="time-slot" data-time="10:30" role="radio" aria-checked="false" tabindex="0">10:30</button>
                            <button type="button" class="time-slot" data-time="14:00" role="radio" aria-checked="false" tabindex="0">14:00</button>
                            <button type="button" class="time-slot" data-time="15:30" role="radio" aria-checked="false" tabindex="0">15:30</button>
                            <button type="button" class="time-slot" data-time="17:00" role="radio" aria-checked="false" tabindex="0">17:00</button>
                            <button type="button" class="time-slot" data-time="18:30" role="radio" aria-checked="false" tabindex="0">18:30</button>
                            <button type="button" class="time-slot" data-time="20:00" role="radio" aria-checked="false" tabindex="0">20:00</button>
                            <button type="button" class="time-slot" data-time="21:30" role="radio" aria-checked="false" tabindex="0">21:30</button>
                        </div>
                        <div class="time-error" id="timeError" role="alert" aria-live="polite">Veuillez sélectionner un créneau horaire.</div>
                    </div>

                    <div class="form-group">
                        <label for="message">Message (optionnel)</label>
                        <textarea id="message" name="message" rows="3" placeholder="Précisez vos objectifs, votre niveau ou vos questions..."></textarea>
                    </div>

                    <button type="submit" class="submit-btn" id="submitBtn">
                        <span class="btn-text">Confirmer la réservation</span>
                        <span class="spinner" aria-hidden="true"></span>
                    </button>
                </form>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div class="social-links">
            <a href="https://instagram.com/chosenoneperf" target="_blank" rel="noopener noreferrer" aria-label="Suivez-nous sur Instagram">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" aria-hidden="true">
                    <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
                    <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
                    <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                </svg>
            </a>
        </div>
        <p class="footer-text">© <span id="currentYear"></span> Chosen One Perf - Coaching Privé Boxe Anglaise</p>
        <p class="instagram-handle">@chosenoneperf</p>
    </footer>

    <!-- Success Modal -->
    <div class="modal" id="successModal" role="dialog" aria-modal="true" aria-labelledby="modalTitle" aria-describedby="modalDesc">
        <div class="modal-content" role="document">
            <div class="modal-icon" aria-hidden="true">✓</div>
            <h3 id="modalTitle">Réservation confirmée !</h3>
            <p id="modalDesc">Votre demande de réservation a bien été enregistrée. Je vous contacterai rapidement pour confirmer votre séance.</p>
            <button class="btn btn-primary" id="modalCloseBtn" onclick="closeModal()" style="width: 100%;">Fermer</button>
        </div>
    </div>

    <script>
        // Année dynamique
        document.getElementById('currentYear').textContent = new Date().getFullYear();

        // Date minimum (aujourd'hui)
        function getTodayLocal() {
            const now = new Date();
            const yyyy = now.getFullYear();
            const mm = String(now.getMonth() + 1).padStart(2, '0');
            const dd = String(now.getDate()).padStart(2, '0');
            return `${yyyy}-${mm}-${dd}`;
        }
        document.getElementById('date').min = getTodayLocal();

        // Gestion des créneaux horaires
        const timeSlots = document.querySelectorAll('.time-slot');
        let selectedTime = null;

        function selectTimeSlot(slot) {
            if (slot.classList.contains('disabled')) return;
            
            // Désélectionner tous
            timeSlots.forEach(s => {
                s.classList.remove('selected');
                s.setAttribute('aria-checked', 'false');
            });
            
            // Sélectionner le nouveau
            slot.classList.add('selected');
            slot.setAttribute('aria-checked', 'true');
            selectedTime = slot.dataset.time;
            
            // Cacher l'erreur
            document.getElementById('timeError').classList.remove('visible');
        }

        timeSlots.forEach(slot => {
            slot.addEventListener('click', () => selectTimeSlot(slot));
            
            slot.addEventListener('keydown', (e) => {
                if (e.key === 'Enter' || e.key === ' ') {
                    e.preventDefault();
                    selectTimeSlot(slot);
                }
            });
        });

        // Navigation mobile
        const burgerBtn = document.getElementById('burgerBtn');
        const mobileMenu = document.getElementById('mobileMenu');

        burgerBtn.addEventListener('click', () => {
            const isOpen = mobileMenu.classList.toggle('open');
            burgerBtn.classList.toggle('open', isOpen);
            burgerBtn.setAttribute('aria-expanded', isOpen);
            document.body.style.overflow = isOpen ? 'hidden' : '';
        });

        function closeMobileMenu() {
            mobileMenu.classList.remove('open');
            burgerBtn.classList.remove('open');
            burgerBtn.setAttribute('aria-expanded', 'false');
            document.body.style.overflow = '';
        }

        // Fermer menu en cliquant ailleurs
        document.addEventListener('click', (e) => {
            if (!burgerBtn.contains(e.target) && !mobileMenu.contains(e.target) && mobileMenu.classList.contains('open')) {
                closeMobileMenu();
            }
        });

        // Fermer avec Escape
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape') {
                if (mobileMenu.classList.contains('open')) {
                    closeMobileMenu();
                }
                if (document.getElementById('successModal').classList.contains('active')) {
                    closeModal();
                }
            }
        });

        // Sélection pack
        function selectPack(pack) {
            document.getElementById('pack').value = pack;
            scrollToBooking();
            // Focus sur le champ date pour continuer
            setTimeout(() => document.getElementById('date').focus(), 600);
        }

        function scrollToBooking() {
            document.getElementById('reservation').scrollIntoView({ behavior: 'smooth' });
        }

        // Soumission formulaire
        document.getElementById('bookingForm').addEventListener('submit', function(e) {
            e.preventDefault();

            // Validation créneau
            if (!selectedTime) {
                const timeError = document.getElementById('timeError');
                timeError.classList.add('visible');
                timeError.scrollIntoView({ behavior: 'smooth', block: 'center' });
                return;
            }

            // Validation native
            if (!this.checkValidity()) {
                this.reportValidity();
                return;
            }

            // Loading state
            const submitBtn = document.getElementById('submitBtn');
            submitBtn.classList.add('loading');
            submitBtn.disabled = true;

            // Simulation envoi
            setTimeout(() => {
                submitBtn.classList.remove('loading');
                submitBtn.disabled = false;
                openModal();
                this.reset();
                selectedTime = null;
                timeSlots.forEach(s => {
                    s.classList.remove('selected');
                    s.setAttribute('aria-checked', 'false');
                });
            }, 1500);
        });

        // Modal
        function openModal() {
            const modal = document.getElementById('successModal');
            modal.classList.add('active');
            document.body.style.overflow = 'hidden';
            document.getElementById('modalCloseBtn').focus();
        }

        function closeModal() {
            const modal = document.getElementById('successModal');
            modal.classList.remove('active');
            document.body.style.overflow = '';
            // Retourner le focus au bouton submit
            document.getElementById('submitBtn').focus();
        }

        document.getElementById('successModal').addEventListener('click', function(e) {
            if (e.target === this) closeModal();
        });

        // Gestion date - désactiver créneaux passés
        document.getElementById('date').addEventListener('change', function() {
            const todayStr = getTodayLocal();
            const isToday = this.value === todayStr;
            const now = new Date();
            const currentHour = now.getHours();
            const currentMinutes = now.getMinutes();

            timeSlots.forEach(slot => {
                slot.classList.remove('disabled');
                slot.setAttribute('aria-disabled', 'false');
                
                if (isToday) {
                    const [slotHour, slotMin] = slot.dataset.time.split(':').map(Number);
                    const slotTotalMinutes = slotHour * 60 + slotMin;
                    const nowTotalMinutes = currentHour * 60 + currentMinutes;

                    if (slotTotalMinutes <= nowTotalMinutes) {
                        slot.classList.add('disabled');
                        slot.setAttribute('aria-disabled', 'true');
                        if (slot.classList.contains('selected')) {
                            slot.classList.remove('selected');
                            slot.setAttribute('aria-checked', 'false');
                            selectedTime = null;
                        }
                    }
                }
            });
        });

        // Intersection Observer pour animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

        // Smooth scroll pour ancres
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });
    </script>
</body>
</html>
