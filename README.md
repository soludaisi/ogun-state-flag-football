 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OGUN STATE FLAG FOOTBALL | Home</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, rgba(0, 100, 0, 0.9) 0%, rgba(218, 165, 32, 0.8) 100%);
        }
        .btn-gold {
            background: linear-gradient(to right, #DAA520, #FFD700);
            transition: all 0.3s ease;
        }
        .btn-gold:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(218, 165, 32, 0.3);
        }
        .border-gold {
            border-color: #DAA520;
        }
        .text-shadow {
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Navigation -->
    <nav class="bg-green-800 text-white shadow-lg">
        <div class="container mx-auto px-4 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <i data-feather="flag" class="text-yellow-300"></i>
                    <span class="font-bold text-xl">OGUN STATE FLAG FOOTBALL</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#" class="hover:text-yellow-300 font-medium">Home</a>
                    <a href="#" class="hover:text-yellow-300 font-medium">Team</a>
                    <a href="#" class="hover:text-yellow-300 font-medium">Schedule</a>
                    <a href="#" class="hover:text-yellow-300 font-medium">Gallery</a>
                    <a href="#" class="hover:text-yellow-300 font-medium">News</a>
                    <a href="#" class="hover:text-yellow-300 font-medium">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <i data-feather="menu"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-gradient text-white py-20 md:py-32">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6 text-shadow" data-aos="fade-down">
                OGUN STATE FLAG FOOTBALL
            </h1>
            <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">
                Dominating the field with speed, strategy, and state pride
            </p>
            <div class="flex justify-center space-x-4" data-aos="fade-up" data-aos-delay="200">
                <a href="#" class="btn-gold text-green-900 font-bold px-6 py-3 rounded-full">
                    View Schedule
                </a>
                <a href="#" class="bg-transparent border-2 border-white text-white font-bold px-6 py-3 rounded-full hover:bg-white hover:text-green-800 transition">
                    Join The Team
                </a>
            </div>
        </div>
    </section>

    <!-- Latest Videos Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-green-800 mb-2" data-aos="fade-up">Latest Game Highlights</h2>
                <div class="w-20 h-1 bg-yellow-500 mx-auto mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">
                    Relive the most exciting moments from our recent matches
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Video 1 -->
                <div class="bg-gray-100 rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition" data-aos="fade-up">
                    <div class="relative pb-[56.25%] bg-black">
                        <img src="http://static.photos/sport/640x360/1" alt="Game Highlight" class="absolute h-full w-full object-cover">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <div class="w-16 h-16 bg-yellow-500 rounded-full flex items-center justify-center">
                                <i data-feather="play" class="text-white"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Season Opener: Ogun vs Lagos</h3>
                        <p class="text-gray-600 mb-4">Watch the explosive first quarter that set the tone for our victory</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i data-feather="calendar" class="mr-2"></i>
                            <span>March 12, 2023</span>
                        </div>
                    </div>
                </div>
                
                <!-- Video 2 -->
                <div class="bg-gray-100 rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition" data-aos="fade-up" data-aos-delay="100">
                    <div class="relative pb-[56.25%] bg-black">
                        <img src="http://static.photos/sport/640x360/2" alt="Game Highlight" class="absolute h-full w-full object-cover">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <div class="w-16 h-16 bg-yellow-500 rounded-full flex items-center justify-center">
                                <i data-feather="play" class="text-white"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Championship Game Highlights</h3>
                        <p class="text-gray-600 mb-4">The final moments that crowned us regional champions</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i data-feather="calendar" class="mr-2"></i>
                            <span>April 28, 2023</span>
                        </div>
                    </div>
                </div>
                
                <!-- Video 3 -->
                <div class="bg-gray-100 rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition" data-aos="fade-up" data-aos-delay="200">
                    <div class="relative pb-[56.25%] bg-black">
                        <img src="http://static.photos/sport/640x360/3" alt="Game Highlight" class="absolute h-full w-full object-cover">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <div class="w-16 h-16 bg-yellow-500 rounded-full flex items-center justify-center">
                                <i data-feather="play" class="text-white"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Player Spotlight: #22's Record Game</h3>
                        <p class="text-gray-600 mb-4">Watch our star receiver break the single-game reception record</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i data-feather="calendar" class="mr-2"></i>
                            <span>May 15, 2023</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12" data-aos="fade-up">
                <a href="#" class="inline-block btn-gold text-green-900 font-bold px-8 py-3 rounded-full">
                    View All Videos
                </a>
            </div>
        </div>
    </section>

    <!-- Photo Gallery Section -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-green-800 mb-2" data-aos="fade-up">Game Day Gallery</h2>
                <div class="w-20 h-1 bg-yellow-500 mx-auto mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">
                    Capturing the intensity, passion, and brotherhood of our team
                </p>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
                <!-- Photo 1 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in">
                    <img src="http://static.photos/sport/640x360/4" alt="Team Photo" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 2 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in" data-aos-delay="100">
                    <img src="http://static.photos/sport/640x360/5" alt="Action Shot" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 3 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in" data-aos-delay="200">
                    <img src="http://static.photos/sport/640x360/6" alt="Celebration" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 4 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in" data-aos-delay="300">
                    <img src="http://static.photos/sport/640x360/7" alt="Training" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 5 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in">
                    <img src="http://static.photos/sport/640x360/8" alt="Team Huddle" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 6 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in" data-aos-delay="100">
                    <img src="http://static.photos/sport/640x360/9" alt="Victory" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 7 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in" data-aos-delay="200">
                    <img src="http://static.photos/sport/640x360/10" alt="Fans" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                
                <!-- Photo 8 -->
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition" data-aos="zoom-in" data-aos-delay="300">
                    <img src="http://static.photos/sport/640x360/11" alt="Action" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
            </div>
            
            <div class="text-center mt-12" data-aos="fade-up">
                <a href="#" class="inline-block bg-green-800 text-white font-bold px-8 py-3 rounded-full hover:bg-green-700 transition">
                    View Full Gallery
                </a>
            </div>
        </div>
    </section>

    <!-- Upcoming Games Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-green-800 mb-2" data-aos="fade-up">Upcoming Games</h2>
                <div class="w-20 h-1 bg-yellow-500 mx-auto mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">
                    Join us for our next battles on the field
                </p>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <!-- Game 1 -->
                <div class="bg-gray-100 rounded-lg p-6 mb-6 shadow-md hover:shadow-lg transition" data-aos="fade-right">
                    <div class="flex flex-col md:flex-row items-center">
                        <div class="flex-1 text-center md:text-left mb-4 md:mb-0">
                            <h3 class="text-xl font-bold text-green-800">Ogun State vs Ekiti Titans</h3>
                            <p class="text-gray-600">Regional Championship Semifinals</p>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Date</div>
                                <div class="font-bold">June 10</div>
                            </div>
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Time</div>
                                <div class="font-bold">4:00 PM</div>
                            </div>
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Venue</div>
                                <div class="font-bold">Abeokuta Stadium</div>
                            </div>
                            <a href="#" class="btn-gold text-green-900 font-bold px-4 py-2 rounded-full text-sm">
                                Get Tickets
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Game 2 -->
                <div class="bg-gray-100 rounded-lg p-6 mb-6 shadow-md hover:shadow-lg transition" data-aos="fade-right" data-aos-delay="100">
                    <div class="flex flex-col md:flex-row items-center">
                        <div class="flex-1 text-center md:text-left mb-4 md:mb-0">
                            <h3 class="text-xl font-bold text-green-800">Ogun State vs Ondo Warriors</h3>
                            <p class="text-gray-600">Regional Championship Finals</p>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Date</div>
                                <div class="font-bold">June 24</div>
                            </div>
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Time</div>
                                <div class="font-bold">4:00 PM</div>
                            </div>
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Venue</div>
                                <div class="font-bold">Abeokuta Stadium</div>
                            </div>
                            <a href="#" class="btn-gold text-green-900 font-bold px-4 py-2 rounded-full text-sm">
                                Get Tickets
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Game 3 -->
                <div class="bg-gray-100 rounded-lg p-6 shadow-md hover:shadow-lg transition" data-aos="fade-right" data-aos-delay="200">
                    <div class="flex flex-col md:flex-row items-center">
                        <div class="flex-1 text-center md:text-left mb-4 md:mb-0">
                            <h3 class="text-xl font-bold text-green-800">Ogun State vs National All-Stars</h3>
                            <p class="text-gray-600">Exhibition Match</p>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Date</div>
                                <div class="font-bold">July 8</div>
                            </div>
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Time</div>
                                <div class="font-bold">3:00 PM</div>
                            </div>
                            <div class="text-center">
                                <div class="text-sm text-gray-500">Venue</div>
                                <div class="font-bold">National Stadium</div>
                            </div>
                            <a href="#" class="btn-gold text-green-900 font-bold px-4 py-2 rounded-full text-sm">
                                Get Tickets
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="py-16 bg-green-800 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4" data-aos="fade-up">Stay Updated</h2>
            <p class="max-w-2xl mx-auto mb-8" data-aos="fade-up" data-aos-delay="100">
                Subscribe to our newsletter for the latest news, game updates, and exclusive content
            </p>
            <form class="max-w-md mx-auto flex" data-aos="fade-up" data-aos-delay="200">
                <input type="email" placeholder="Your email address" class="flex-1 px-4 py-3 rounded-l-full focus:outline-none text-gray-800">
                <button type="submit" class="bg-yellow-500 text-green-900 font-bold px-6 py-3 rounded-r-full hover:bg-yellow-400 transition">
                    Subscribe
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <i data-feather="flag" class="text-yellow-300 mr-2"></i>
                        OGUN STATE FLAG FOOTBALL
                    </h3>
                    <p class="text-gray-400">
                        The premier flag football team representing Ogun State with pride, passion, and excellence.
                    </p>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-yellow-300 transition">Home</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-yellow-300 transition">Team Roster</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-yellow-300 transition">Game Schedule</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-yellow-300 transition">Photo Gallery</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-yellow-300 transition">Contact Us</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Follow Us</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-yellow-500 hover:text-gray-900 transition">
                            <i data-feather="facebook"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-yellow-500 hover:text-gray-900 transition">
                            <i data-feather="twitter"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-yellow-500 hover:text-gray-900 transition">
                            <i data-feather="instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-yellow-500 hover:text-gray-900 transition">
                            <i data-feather="youtube"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Contact</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-center">
                            <i data-feather="map-pin" class="mr-2"></i>
                            Abeokuta Stadium, Ogun State
                        </li>
                        <li class="flex items-center">
                            <i data-feather="mail" class="mr-2"></i>
                            info@ogunflagfootball.com
                        </li>
                        <li class="flex items-center">
                            <i data-feather="phone" class="mr-2"></i>
                            +234 123 456 7890
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
                <p>&copy; 2023 Ogun State Flag Football. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });
    </script>
    <script>
        feather.replace();
    </script>
</body>
</html>
