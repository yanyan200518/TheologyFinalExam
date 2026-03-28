<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SEC Digital Magazine Portfolio | Theology 103</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400;1,600&family=Source+Sans+Pro:wght@300;400;600&display=swap" rel="stylesheet">
    <!-- Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <!-- PageFlip Library -->
    <script src="https://cdn.jsdelivr.net/npm/page-flip/dist/js/page-flip.browser.min.js"></script>

    <style>
        body {
            font-family: 'Source Sans Pro', sans-serif;
            background-color: #1a1a1a; /* Dark background to make the magazine pop */
            background-image: radial-gradient(circle at center, #2a2a2a 0%, #111 100%);
            color: #333;
            margin: 0;
        }
        h1, h2, h3, h4, .magazine-title {
            font-family: 'Playfair Display', serif;
        }
        
        /* Magazine Page Styles */
        .page {
            background-color: #fdfbf7;
            box-shadow: inset 0 0 20px rgba(0,0,0,0.02);
            overflow: hidden;
        }
        /* Hide scrollbars but allow scrolling inside pages if content is too long on small screens */
        .page-content {
            height: 100%;
            overflow-y: auto;
            -ms-overflow-style: none;  /* IE and Edge */
            scrollbar-width: none;  /* Firefox */
        }
        .page-content::-webkit-scrollbar {
            display: none;
        }
        
        .page-left {
            border-right: 1px solid rgba(0,0,0,0.1);
        }
        .page-right {
            border-left: 1px solid rgba(0,0,0,0.1);
        }

        .drop-cap::first-letter {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            font-weight: bold;
            float: left;
            line-height: 0.8;
            margin-top: 0.15em;
            margin-right: 0.1em;
            color: #991b1b; /* Crimson Red */
        }
        
        .placeholder-img {
            background-color: #fef2f2; /* Light crimson tint */
            display: flex;
            align-items: center;
            justify-content: center;
            color: #991b1b;
            text-align: center;
            border: 2px dashed #fca5a5;
            transition: all 0.3s ease;
        }
        .placeholder-img:hover {
            background-color: #fee2e2;
            border-color: #ef4444;
        }

        /* Hardcover simulation for first and last page */
        .page.--cover {
            background-color: #fdfbf7;
        }
    </style>
</head>
<body class="antialiased min-h-screen flex flex-col items-center py-8 md:py-12">

    <!-- Magazine Wrapper -->
    <div class="w-full flex flex-col items-center px-4 my-auto">
        
        <!-- Controls -->
        <div class="flex justify-between items-center w-full max-w-4xl mb-6 px-4 z-10">
            <button id="prevBtn" class="flex items-center gap-2 px-4 py-2 bg-red-800 hover:bg-red-700 text-white rounded shadow-lg transition duration-200 uppercase tracking-wider text-sm font-semibold">
                <i data-lucide="chevron-left" class="w-4 h-4"></i> Prev
            </button>
            <span id="page-counter" class="text-gray-300 font-serif tracking-widest text-sm uppercase">Page 1 of 10</span>
            <button id="nextBtn" class="flex items-center gap-2 px-4 py-2 bg-red-800 hover:bg-red-700 text-white rounded shadow-lg transition duration-200 uppercase tracking-wider text-sm font-semibold">
                Next <i data-lucide="chevron-right" class="w-4 h-4"></i>
            </button>
        </div>

        <!-- The Book Container -->
        <div id="magazine" class="shadow-2xl shadow-black/50">
            
            <!-- PAGE 1: Front Cover -->
            <div class="page --cover" data-density="hard">
                <div class="page-content p-8 md:p-12 flex flex-col justify-center items-center text-center">
                    <div class="w-full h-full border-4 border-red-800 p-6 flex flex-col justify-center items-center relative">
                        <div class="absolute top-6 w-full flex flex-col items-center">
                            <img src="https://i.ibb.co/5xrttdNk/logo-circle-2.png" alt="HAU Logo" class="w-16 h-16 object-contain mb-2">
                            <div class="text-[10px] md:text-xs font-semibold tracking-[0.3em] uppercase text-red-800">Theology 103 Final</div>
                        </div>
                        
                        <h3 class="text-xs md:text-sm tracking-[0.2em] uppercase mb-6 text-gray-600 font-semibold mt-20">Spiritual Encounter Convocation</h3>
                        <h1 class="text-5xl md:text-6xl font-bold mb-6 text-gray-900 leading-tight">Carrying Christ's Light <br><span class="italic font-normal text-red-800">into the World</span></h1>
                        <p class="text-base text-gray-700 mb-10 font-light max-w-sm">Discovering faith, communion, and growth by gathering around the same table.</p>
                        
                        <!-- COVER IMAGE -->
                        <div class="w-full h-64 mt-auto rounded shadow-inner relative overflow-hidden border border-gray-200">
                            <img src="https://i.ibb.co/xqh2vY4x/3dfdfd0b680d6b264f5530206b0bcbd0.jpg" alt="SEC Implementation" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>

            <!-- PAGE 2: Inside Cover (3Cs) -->
            <div class="page page-left">
                <div class="page-content p-8 md:p-12 flex flex-col justify-center bg-stone-100">
                    <h2 class="text-3xl font-bold mb-6 text-red-800 border-b-2 border-red-800 pb-2 inline-block">Embracing the 3Cs</h2>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        Our SEC portfolio is a testament to our collective journey of faith. Guided by our university's core values—<strong class="text-gray-900">Conscience, Competence, and Compassion</strong>—we discovered that carrying Christ's light into the world begins with small, authentic interactions. 
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        This digital magazine documents how we translated these values into action. Turn the pages to explore our reflections, shared moments, and spiritual growth.
                    </p>
                    <div class="mt-12 opacity-20 flex justify-center">
                        <i data-lucide="book-open" class="w-32 h-32 text-red-800"></i>
                    </div>
                </div>
            </div>

            <!-- PAGE 3: SEC Summary (Text) -->
            <div class="page page-right">
                <div class="page-content p-8 md:p-12">
                    <h4 class="text-xs font-bold tracking-widest uppercase text-red-700 mb-2">01. SEC Summary</h4>
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6 leading-tight">Key Themes & Insights</h2>
                    <p class="text-base text-gray-700 leading-relaxed drop-cap mb-4">
                        Our SEC experience revolved around the idea that, despite our different backgrounds, we all begin in the same place <strong>"around the same table."</strong> This table is not just a physical space but a symbol of connection, where we share stories, listen, pray, forgive, and grow together. It represents a safe space where faith is lived through real relationships and everyday encounters rather than perfection.
                    </p>
                    <p class="text-base text-gray-700 leading-relaxed mb-4">
                        Through the Spiritual Growth Chart, family traditions, and Bible sharing, we realized that faith is not something fixed or complete. Instead, it is a continuous journey. As young people, we are still learning, still growing, and still becoming.
                    </p>
                    <p class="text-base text-gray-700 leading-relaxed">
                        We came to understand that faith becomes more meaningful when it is shared. Around the same table, we were able to express our thoughts freely, reflect on our experiences, and support one another.
                    </p>
                </div>
            </div>

            <!-- PAGE 4: SEC Summary (Image) -->
            <div class="page page-left">
                <div class="page-content p-8 md:p-12 flex flex-col justify-center">
                    <div class="w-full h-full min-h-[400px] rounded shadow-md border-2 border-red-200 overflow-hidden bg-gray-100">
                        <img src="https://i.ibb.co/5hWKC5xb/Screenshot-2026-03-28-at-8-05-42-PM.png" alt="Group Recollection and Reflection" class="w-full h-full object-cover object-center">
                    </div>
                    <p class="text-center text-sm text-gray-500 italic mt-4">Faith is strengthened through community.</p>
                </div>
            </div>

            <!-- PAGE 5: Spiritual Journey (Text) -->
            <div class="page page-right">
                <div class="page-content p-8 md:p-12">
                    <h4 class="text-xs font-bold tracking-widest uppercase text-red-700 mb-2">02. Personal Reflections</h4>
                    <h2 class="text-3xl md:text-4xl font-bold leading-tight mb-6">Spiritual Journey Highlights</h2>
                    <p class="text-base text-gray-700 leading-relaxed mb-4">
                        Before the SEC, we both had our own ways of understanding faith, influenced by our personal experiences and family backgrounds. At times, we focused more on our individual lives and less on how God was present in our everyday actions. However, through the activities and reflections, we began to see that faith is not separate from our daily lives.
                    </p>
                    <p class="text-base text-gray-700 leading-relaxed mb-6">
                        The Spiritual Growth Chart helped us reflect honestly on where we are in our spiritual journey. We realized that while we are strong in showing love, compassion, and care for others, we still struggle with consistency in prayer, forgiveness, service, and inner peace. 
                    </p>
                    <blockquote class="border-l-4 border-red-800 pl-4 py-2 mb-6 italic text-lg text-gray-900 font-serif bg-red-50 pr-4">
                        "We found comfort in knowing that we share similar struggles. Being able to talk openly without fear of judgment made us realize spiritual growth is a shared journey."
                    </blockquote>
                    <p class="text-base text-gray-700 leading-relaxed">
                        We are still learning to trust more, to be more patient, and to deepen our relationship with God step by step.
                    </p>
                </div>
            </div>

            <!-- PAGE 6: Spiritual Journey (Image) -->
            <div class="page page-left">
                <div class="page-content p-8 md:p-12 flex flex-col justify-center bg-stone-900 text-white">
                    <div class="w-full h-[400px] !border-red-900 rounded shadow-2xl mb-8 overflow-hidden bg-black">
                        <img src="https://i.ibb.co/5hc95K2f/Screenshot-2026-03-28-at-8-03-47-PM.png" alt="Spiritual Journey" class="w-full h-full object-cover object-center opacity-90 hover:opacity-100 transition-opacity">
                    </div>
                    <div class="text-center max-w-sm mx-auto">
                        <h3 class="text-xl font-serif text-red-400 mb-2">A Continuous Journey</h3>
                        <p class="text-sm text-stone-300">Recognizing that our faith is still incomplete and continues to develop.</p>
                    </div>
                </div>
            </div>

            <!-- PAGE 7: Table Fellowship -->
            <div class="page page-right">
                <div class="page-content p-8 md:p-12">
                    <h4 class="text-xs font-bold tracking-widest uppercase text-red-700 mb-2">04. Breaking of Bread</h4>
                    <h2 class="text-3xl font-bold text-gray-900 mb-4">Table Fellowship Reflection</h2>
                    
                    <div class="w-full h-40 rounded shadow mb-6 overflow-hidden bg-gray-100">
                        <img src="https://i.ibb.co/tw68LqLj/Screenshot-2026-03-28-at-8-03-41-PM.png" alt="Egg Burger Table Fellowship" class="w-full h-full object-cover object-top">
                    </div>

                    <p class="text-sm text-gray-700 leading-relaxed mb-3">
                        The "Breaking of Bread" activity was a beautiful reminder of what fellowship is really about connecting with others through shared meals, honest conversations, and faith. As we sat together, we realized that sharing an egg burger can create a real sense of comfort, trust, and belonging.
                    </p>
                    <p class="text-sm text-gray-700 leading-relaxed mb-3">
                        Fellowship is more than eating in the same room; it’s about truly being present. Building trust takes heart and patience. As we spent time together, quiet members started to open up.
                    </p>
                    <p class="text-sm text-gray-700 leading-relaxed font-semibold text-red-900">
                        Inclusivity happens through small, everyday acts of kindness. The act of "breaking bread" felt like a tangible way to share love. Faith isn’t just found in scripture, but in the compassion we show one another.
                    </p>
                </div>
            </div>

            <!-- PAGE 8: Visuals -->
            <div class="page page-left">
                <div class="page-content p-8 md:p-12">
                    <h4 class="text-xs font-bold tracking-widest uppercase text-red-700 mb-2">03. Captured Moments</h4>
                    <h2 class="text-3xl font-bold text-gray-900 mb-6">Visuals: SEC Experience</h2>
                    
                    <div class="grid grid-cols-1 gap-4 mb-6">
                        <div class="h-40 rounded shadow-sm overflow-hidden bg-gray-100 border border-gray-200">
                            <img src="https://i.ibb.co/8g8M6Wgq/Screenshot-2026-03-28-at-8-03-58-PM.png" alt="Fellowship Visual 1" class="w-full h-full object-cover object-top">
                        </div>
                        <div class="h-40 rounded shadow-sm overflow-hidden bg-gray-100 border border-gray-200">
                            <img src="https://i.ibb.co/5hc95K2f/Screenshot-2026-03-28-at-8-03-47-PM.png" alt="Fellowship Visual 2" class="w-full h-full object-cover object-center">
                        </div>
                    </div>

                    <p class="text-sm text-gray-700 leading-relaxed">
                        These visuals remind us that our journey was not done alone. They show how faith and learning become more meaningful when experienced with others, serving as proof that the SEC was not just about understanding concepts but about living them together.
                    </p>
                </div>
            </div>

            <!-- PAGE 9: Multimedia & Teamwork -->
            <div class="page page-right">
                <div class="page-content p-8 md:p-12">
                    <!-- Multimedia -->
                    <div class="mb-8 border-b border-gray-200 pb-6">
                        <h4 class="text-xs font-bold tracking-widest uppercase text-red-700 mb-1">05. Unveiling Angelite</h4>
                        <h2 class="text-2xl font-bold text-gray-900 mb-3">Multimedia Integration</h2>
                        <div class="w-full h-32 rounded mb-3 overflow-hidden shadow-sm border border-gray-200">
                            <img src="https://i.ibb.co/TDxJ6bRy/Screenshot-2026-03-28-at-8-03-07-PM.png" alt="Unveiling the Angelite Charism" class="w-full h-full object-cover object-top">
                        </div>
                        <p class="text-sm text-gray-700 leading-relaxed">
                            Our "Unveiling Angelite" project reflects connection and shared growth. This project became a representation of our journey, showing how creativity can be used to express faith.
                        </p>
                    </div>

                    <!-- Teamwork -->
                    <div>
                        <h4 class="text-xs font-bold tracking-widest uppercase text-red-700 mb-1">06. Walking Together</h4>
                        <h2 class="text-2xl font-bold text-gray-900 mb-3">Teamwork Evidence</h2>
                        <p class="text-sm text-gray-700 leading-relaxed mb-3">
                            Throughout the SEC, teamwork played an important role. We consistently worked together, respected differences, and supported one another.
                        </p>
                        <div class="w-full h-32 rounded mb-3 overflow-hidden shadow-sm border border-gray-200">
                            <img src="https://i.ibb.co/xqh2vY4x/3dfdfd0b680d6b264f5530206b0bcbd0.jpg" alt="SEC Implementation Teamwork" class="w-full h-full object-cover object-center">
                        </div>
                    </div>
                </div>
            </div>

            <!-- PAGE 10: Back Cover -->
            <div class="page --cover" data-density="hard">
                <div class="page-content p-8 md:p-12 flex flex-col justify-center items-center text-center bg-stone-900 text-white border-l-4 border-red-800">
                    <i data-lucide="flame" class="w-16 h-16 text-red-600 mb-6"></i>
                    <h3 class="text-3xl font-serif mb-4">Carrying Christ's Light<br>into the World</h3>
                    <div class="w-16 h-1 bg-red-700 mx-auto mb-8"></div>
                    
                    <p class="text-sm text-stone-400 uppercase tracking-widest mb-8">Group Assessment Portfolio</p>
                    
                    <div class="flex flex-col space-y-3 font-serif text-lg text-red-200">
                        <span>Conscience</span>
                        <span>Competence</span>
                        <span>Compassion</span>
                    </div>

                    <p class="mt-auto pt-12 text-xs text-stone-500 tracking-wide">&copy; 2026 Theology 103 Students.<br>All rights reserved.</p>
                </div>
            </div>

        </div>
    </div>

    <!-- Magazine Flip Script -->
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Initialize Lucide Icons
            lucide.createIcons();

            // Initialize PageFlip
            const bookContainer = document.getElementById('magazine');
            
            const pageFlip = new St.PageFlip(bookContainer, {
                width: 500, // Base width of a single page
                height: 700, // Base height
                size: "stretch", // Stretch to fit the container constraints
                minWidth: 315,
                maxWidth: 550,
                minHeight: 450,
                maxHeight: 750,
                maxShadowOpacity: 0.3,
                showCover: true, // First and last pages are single covers
                mobileScrollSupport: false, // Disables native scrolling on mobile to prioritize flipping
                usePortrait: true // Allows single-page viewing on mobile screens
            });

            // Load pages from DOM
            const pages = document.querySelectorAll('.page');
            pageFlip.loadFromHTML(pages);

            // Update Page Counter and Handle Controls
            const prevBtn = document.getElementById('prevBtn');
            const nextBtn = document.getElementById('nextBtn');
            const pageCounter = document.getElementById('page-counter');
            const totalPages = pages.length;

            pageFlip.on('flip', (e) => {
                // e.data is the current page index (starts at 0)
                let currentPageStr = '';
                
                // Formatting the page number display based on desktop (2 pages) or mobile (1 page)
                if (pageFlip.getOrientation() === 'landscape') {
                    if (e.data === 0) {
                        currentPageStr = `Page 1 of ${totalPages}`;
                    } else if (e.data === totalPages - 1) {
                        currentPageStr = `Page ${totalPages} of ${totalPages}`;
                    } else {
                        currentPageStr = `Pages ${e.data + 1}-${e.data + 2} of ${totalPages}`;
                    }
                } else {
                    currentPageStr = `Page ${e.data + 1} of ${totalPages}`;
                }
                
                pageCounter.innerText = currentPageStr;
            });

            // Button Click Events
            prevBtn.addEventListener('click', () => {
                pageFlip.flipPrev();
            });

            nextBtn.addEventListener('click', () => {
                pageFlip.flipNext();
            });
        });
    </script>
</body>
</html>
