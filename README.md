# makvic--site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Makvic - Premium Study Materials</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/js/all.min.js"></script>
</head>
<body class="bg-white font-sans">
    <!-- Navigation -->
    <nav class="bg-indigo-700 text-white sticky top-0 z-50 shadow-xl">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <a href="#" class="text-3xl font-bold tracking-tight hover:text-indigo-200 transition-colors">
                    Makvic<span class="text-indigo-300">.</span>
                </a>
                <div class="hidden md:flex items-center space-x-10">
                    <a href="#" class="nav-link hover:text-indigo-200 font-medium">Home</a>
                    <a href="#products" class="nav-link hover:text-indigo-200 font-medium">Products</a>
                    <a href="#about" class="nav-link hover:text-indigo-200 font-medium">About</a>
                    <a href="#contact" class="nav-link hover:text-indigo-200 font-medium">Contact</a>
                </div>
                <button class="md:hidden text-2xl focus:outline-none">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
    </nav>
    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-indigo-900 to-purple-900 text-white py-24">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-12 md:mb-0">
                    <h1 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">Excel in Your Studies with <span class="text-indigo-300">Premium Materials</span></h1>
                    <p class="text-xl text-indigo-100 mb-10 max-w-lg">Access high-quality notes, past papers and revision guides curated by top students.</p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#products" class="bg-white text-indigo-900 hover:bg-indigo-100 font-bold py-4 px-8 rounded-full transition-all duration-300 transform hover:scale-105 shadow-lg">
                            Browse Products <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                        <a href="#about" class="border-2 border-white text-white hover:bg-white hover:text-indigo-900 font-medium py-4 px-8 rounded-full transition-all duration-300">
                            Learn More
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <img src="http://static.photos/education/1024x576/1" alt="Study Materials" class="rounded-2xl shadow-2xl transform hover:scale-105 transition-transform duration-500">
                </div>
            </div>
        </div>
    </section>
<!-- Search Bar -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-md mx-auto">
                <div class="relative flex items-center">
                    <input type="text" placeholder="Search study materials..." class="w-full py-3 px-4 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                    <button class="absolute right-3 bg-blue-600 text-white p-2 rounded-lg">
                        <i class="fas fa-search"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Our Study Materials</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-xl transition duration-300">
                    <img src="http://static.photos/education/320x240/2" alt="Comprehensive Notes" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Comprehensive Notes</h3>
                        <p class="text-gray-600 mb-4">Detailed subject notes covering all key topics.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-600 font-bold">KES 500</span>
                            <a href="https://wa.me/2547XXXXXXXX?text=I%20want%20to%20buy%20Comprehensive%20Notes%20for%20KES%20500" class="bg-green-500 hover:bg-green-600 text-white py-2 px-4 rounded-lg transition duration-300 flex items-center">
                                <i class="fab fa-whatsapp mr-2"></i> Buy Now
                            </a>
</div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-xl transition duration-300">
                    <img src="http://static.photos/education/320x240/3" alt="Past Papers" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Past Papers Collection</h3>
                        <p class="text-gray-600 mb-4">10 years of past papers with marking schemes.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-600 font-bold">KES 800</span>
                            <a href="https://wa.me/2547XXXXXXXX?text=I%20want%20to%20buy%20Past%20Papers%20Collection%20for%20KES%20800" class="bg-green-500 hover:bg-green-600 text-white py-2 px-4 rounded-lg transition duration-300 flex items-center">
                                <i class="fab fa-whatsapp mr-2"></i> Buy Now
                            </a>
</div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-xl transition duration-300">
                    <img src="http://static.photos/education/320x240/4" alt="Revision Guides" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Revision Guides</h3>
                        <p class="text-gray-600 mb-4">Condensed materials for last-minute revision.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-600 font-bold">KES 600</span>
                            <a href="https://wa.me/2547XXXXXXXX?text=I%20want%20to%20buy%20Revision%20Guides%20for%20KES%20600" class="bg-green-500 hover:bg-green-600 text-white py-2 px-4 rounded-lg transition duration-300 flex items-center">
                                <i class="fab fa-whatsapp mr-2"></i> Buy Now
                            </a>
</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">What Students Say</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-blue-50 p-6 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                            <i class="fas fa-user text-blue-600"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-semibold">Sarah K.</h4>
                            <p class="text-blue-600">University Student</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"Makvic's notes helped me improve my grades significantly. The material is well-organized and easy to understand."</p>
                </div>

                <!-- Testimonial 2 -->
                <div class="bg-blue-50 p-6 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                            <i class="fas fa-user text-blue-600"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-semibold">James M.</h4>
                            <p class="text-blue-600">High School Student</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"The past papers collection was exactly what I needed for my exam preparation. Highly recommended!"</p>
                </div>

                <!-- Testimonial 3 -->
                <div class="bg-blue-50 p-6 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                            <i class="fas fa-user text-blue-600"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-semibold">Grace W.</h4>
                            <p class="text-blue-600">College Student</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"I love the revision guides - they save me so much time and help me focus on what's important."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-blue-600 text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Get In Touch</h2>
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h3 class="text-xl font-semibold mb-4">Contact Information</h3>
                    <p class="mb-4"><i class="fas fa-map-marker-alt mr-2"></i> Nairobi, Kenya</p>
                    <p class="mb-4"><i class="fas fa-phone mr-2"></i> +254 700 123 456</p>
                    <p class="mb-4"><i class="fas fa-envelope mr-2"></i> info@makvic.com</p>
                </div>
                <div class="md:w-1/2">
                    <form>
                        <div class="mb-4">
                            <input type="text" placeholder="Your Name" class="w-full px-4 py-3 rounded-lg bg-blue-700 text-white placeholder-blue-300 focus:outline-none focus:ring-2 focus:ring-white">
                        </div>
                        <div class="mb-4">
                            <input type="email" placeholder="Your Email" class="w-full px-4 py-3 rounded-lg bg-blue-700 text-white placeholder-blue-300 focus:outline-none focus:ring-2 focus:ring-white">
                        </div>
                        <div class="mb-4">
                            <textarea placeholder="Your Message" rows="4" class="w-full px-4 py-3 rounded-lg bg-blue-700 text-white placeholder-blue-300 focus:outline-none focus:ring-2 focus:ring-white"></textarea>
                        </div>
                        <button type="submit" class="bg-white text-blue-600 font-bold py-3 px-6 rounded-lg hover:bg-gray-100 transition duration-300">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center max-w-4xl mx-auto">
                <h2 class="text-4xl font-bold text-gray-800 mb-6">About Makvic</h2>
                <p class="text-xl text-gray-600 mb-10">We're a team of educators and top students committed to helping you succeed academically through high-quality study materials.</p>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="bg-indigo-50 p-8 rounded-xl shadow-lg">
                        <div class="text-indigo-600 text-4xl mb-4">
                            <i class="fas fa-graduation-cap"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Expert-Curated</h3>
                        <p class="text-gray-600">Materials created and reviewed by top-performing students.</p>
                    </div>
                    <div class="bg-purple-50 p-8 rounded-xl shadow-lg">
                        <div class="text-purple-600 text-4xl mb-4">
                            <i class="fas fa-check-circle"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Quality Guaranteed</h3>
                        <p class="text-gray-600">Rigorously tested and updated materials for accuracy.</p>
                    </div>
                    <div class="bg-blue-50 p-8 rounded-xl shadow-lg">
                        <div class="text-blue-600 text-4xl mb-4">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Results-Driven</h3>
                        <p class="text-gray-600">Proven to help students improve their grades.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-12">
                <div>
                    <h3 class="text-2xl font-bold mb-4">Makvic<span class="text-indigo-400">.</span></h3>
                    <p class="text-gray-400 mb-4">Premium study materials for academic excellence.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white text-xl"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white text-xl"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white text-xl"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white text-xl"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Home</a></li>
                        <li><a href="#products" class="text-gray-400 hover:text-white">Products</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Contact</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center text-gray-400"><i class="fas fa-map-marker-alt mr-3"></i> Nairobi, Kenya</li>
                        <li class="flex items-center text-gray-400"><i class="fas fa-phone mr-3"></i> +254 700 123 456</li>
                        <li class="flex items-center text-gray-400"><i class="fas fa-envelope mr-3"></i> info@makvic.com</li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Newsletter</h4>
                    <p class="text-gray-400 mb-4">Subscribe for study tips and new materials.</p>
                    <div class="flex">
                        <input type="email" placeholder="Your email" class="px-4 py-2 w-full rounded-l-lg focus:outline-none text-gray-900">
                        <button class="bg-indigo-600 hover:bg-indigo-700 px-4 rounded-r-lg">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
                <p>&copy; 2023 Makvic. All rights reserved.</p>
            </div>
        </div>
    </footer>
<script src="script.js"></script>
</body>
</html>
