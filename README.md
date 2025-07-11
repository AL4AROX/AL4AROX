<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROXITO | Portafolio Glitch</title>
    <style>
        /* FUENTES PIXELADAS */
        @import url('https://fonts.googleapis.com/css2?family=Silkscreen:wght@400;700&family=Press+Start+2P&display=swap');
        
        :root {
            --negro: #000000;
        }
        
        body {
            background-color: var(--negro);
            color: white;
            font-family: 'Silkscreen', cursive;
            margin: 0;
            line-height: 1.6;
        }
        
        /* EFECTO RGB EN TÍTULOS */
        .rgb-text {
            animation: rgb-cycle 3s infinite;
        }
        
        @keyframes rgb-cycle {
            0% { color: #ff0000; text-shadow: 0 0 15px #ff0000; }
            33% { color: #00fffc; text-shadow: 0 0 15px #00fffc; }
            66% { color: #ff00f2; text-shadow: 0 0 15px #ff00f2; }
            100% { color: #ff0000; text-shadow: 0 0 15px #ff0000; }
        }
        
        /* ESTRUCTURA */
        section {
            padding: 2rem;
            max-width: 800px;
            margin: 0 auto 3rem auto;
            border: 1px solid #00fffc;
            position: relative;
            background: rgba(0, 0, 0, 0.7);
        }
        
        h1 {
            font-size: 3rem;
            text-align: center;
            margin-bottom: 1rem;
        }
        
        h2 {
            font-size: 2rem;
            border-bottom: 3px solid #ff00f2;
            padding-bottom: 0.5rem;
            margin-top: 3rem;
            display: inline-block;
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 2rem 0 1rem 0;
        }
        
        /* SERVICIOS - LISTA DETALLADA */
        .servicio {
            margin-bottom: 2rem;
            padding-left: 1rem;
            border-left: 3px solid;
        }
        
        .servicio h4 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: #00fffc;
        }
        
        .servicio p {
            margin: 0.5rem 0;
            padding-left: 1rem;
        }
        
        /* CONTACTO - EFECTO ESPECIAL */
        #contacto {
            text-align: center;
            background: rgba(0, 0, 0, 0.9);
            border: 2px dashed #00fffc;
        }
        
        .btn-contacto {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            margin: 1rem;
            background: black;
            color: white;
            border: 2px solid #ff00f2;
            font-family: 'Press Start 2P', cursive;
            font-size: 0.9rem;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .btn-contacto:hover {
            background: #ff00f2;
            box-shadow: 0 0 20px #ff00f2;
        }
        
        /* EFECTO GLITCH EN PÁRRAFOS */
        p {
            position: relative;
        }
        
        p::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(
                to bottom,
                transparent,
                transparent 50%,
                rgba(0, 255, 252, 0.05) 50%,
                rgba(0, 255, 252, 0.05)
            );
            background-size: 100% 4px;
            pointer-events: none;
        }
    </style>
</head>
<body>
    <!-- PRESENTACIÓN -->
    <section>
        <h1 class="rgb-text">ROXITO</h1>
        <p style="text-align: center; font-size: 1.3rem;" class="rgb-text">STAFF PROFESIONAL MINECRAFT</p>
        <p>
            Hola, soy Álvaro "Roxito". Staff con 1 año de experiencia en moderación, anti-cheat y gestión de comunidades.
        </p>
    </section>
    
    <!-- EXPERIENCIA -->
    <section>
        <h2 class="rgb-text">EXPERIENCIA</h2>
        
        <h3 class="rgb-text">FearMC (2025)</h3>
        <ul>
            <li><strong>Rango:</strong> Moderador → Administrador</li>
            <li><strong>Tickets atendidos:</strong> 400+</li>
            <li><strong>Sanciones aplicadas:</strong> 500+</li>
            <li><strong>Logro:</strong> Staff más activo (3 meses consecutivos)</li>
        </ul>
        
        <h3 class="rgb-text">Mineskull (2024-2025)</h3>
        <ul>
            <li><strong>Rango:</strong> Staff Manager</li>
            <li><strong>Tickets atendidos:</strong> 100 en 15 días</li>
            <li><strong>Sistemas creados:</strong> Reglamento SS + guía de sanciones</li>
        </ul>
    </section>
    
    <!-- PROYECTOS -->
    <section>
        <h2 class="rgb-text">PROYECTOS</h2>
        
        <h3 class="rgb-text">HELP CONSOLE</h3>
        <ul>
            <li>Script PowerShell para training de staff</li>
            <li>Incluye: flujo de tickets, detección de hacks</li>
            <li>Estado: En desarrollo</li>
        </ul>
        
        <h3 class="rgb-text">DINAMIX STUDIO</h3>
        <ul>
            <li>Estudio de construcción (BoxPvP/lobbys)</li>
            <li>Trabajos personalizados para servidores</li>
        </ul>
    </section>
    
    <!-- SERVICIOS COMPLETOS -->
    <section>
        <h2 class="rgb-text">SERVICIOS</h2>
        
        <div class="servicio">
            <h4>MODERACIÓN</h4>
            <p>
                Superviso el server durante la mayoría del tiempo que dedico al servidor; hago la experiencia de juego más agradable, 
                intentando crear una mejor experiencia sin hackers. También superviso posibles estafas y hago tradeos justos para evitarlas, 
                además de supervisar el chat constantemente para evitar insultos, mención de otros servers o cualquier comportamiento tóxico.
            </p>
        </div>
        
        <div class="servicio">
            <h4>ATENCIÓN AGRADABLE</h4>
            <p>
                Ya sea respondiendo dudas en chat general, soporte comunitario o en un ticket, nunca falta el buen trato hacia el jugador, 
                para que se lleve un buen sabor de boca del server. Modales, profesionalidad y asistencia rápida es lo que ofrezco en 
                Discord o TeamSpeak. Mi tiempo promedio de respuesta en tickets es menor a 5 minutos.
            </p>
        </div>
        
        <div class="servicio">
            <h4>GUÍAS ELABORADAS</h4>
            <p>
                Hago guías personalizadas de sanciones, reglas o SS, siempre ajustadas al estilo del servidor. Estas guías sirven para 
                orientar a compañeros del staff sobre cómo actuar en diferentes situaciones. Incluyen ejemplos visuales, pasos detallados 
                y protocolos para casos complejos.
            </p>
        </div>
        
        <div class="servicio">
            <h4>AYUDA A STAFF</h4>
            <p>
                Aparte de ayudar a jugadores, siempre estoy dispuesto a apoyar a staff de menor rango o experiencia. Les explico cómo 
                mejorar en atención al público, revisión de pruebas, manejo de plugins y profesionalidad. He entrenado personalmente a 
                15+ moderadores en diferentes servidores.
            </p>
        </div>
        
        <div class="servicio">
            <h4>POLÍTICA DE PAGOS</h4>
            <p>
                No cobro por servicios de staff. Nunca he pedido ni aceptaré dinero por rangos o privilegios. Hago esto por pasión a los 
                servidores Minecraft y por ayudar a crear comunidades sanas.
            </p>
        </div>
    </section>
    
    <!-- CONTACTO -->
    <section id="contacto">
        <h2 class="rgb-text">CONTACTO</h2>
        <p>¿Interesado en mi trabajo?</p>
        
        <button class="btn-contacto" data-text="alvarox504gmail.com">📧 EMAIL</button>
        <button class="btn-contacto" data-text="alvaro43v_46936">💬 DISCORD</button>
        
        <p style="margin-top: 1.5rem;">¡Haz clic para copiar!</p>
    </section>
    
    <!-- FOOTER -->
    <section style="text-align: center; border: none; margin-bottom: 0;">
        <p>© 2025 ROXITO - PORTAFOLIO OFICIAL</p>
    </section>

    <!-- SCRIPTS -->
    <script>
        // Botones de copiado
        document.querySelectorAll('.btn-contacto').forEach(btn => {
            btn.addEventListener('click', function() {
                const text = this.getAttribute('data-text');
                navigator.clipboard.writeText(text);
                
                // Efecto visual
                this.style.background = '#00fffc';
                this.style.color = 'black';
                setTimeout(() => {
                    this.style.background = 'black';
                    this.style.color = 'white';
                }, 500);
            });
        });
    </script>
</body>
</html>
