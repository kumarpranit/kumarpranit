<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Showcase</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for Inter font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary': '#4f46e5',
                        'primary-dark': '#4338ca',
                        'secondary': '#f97316',
                    }
                }
            }
        }
    </script>
    <!-- Use Inter font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <!-- Custom styling for icons/placeholders -->
    <style>
        .cert-icon {
            /* Placeholder for a nice, rounded icon background */
            width: 3rem;
            height: 3rem;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 9999px; /* fully rounded */
        }
        .cert-card {
            transition: all 0.3s ease;
        }
        .cert-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px -5px rgba(0, 0, 0, 0.1), 0 8px 16px -8px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body class="bg-gray-50 font-sans p-4 sm:p-8">

    <div class="max-w-4xl mx-auto">
        
        <!-- MAIN HEADER / BIO SECTION -->
        <header class="text-center mb-16 p-8 bg-white rounded-xl shadow-lg border-t-4 border-primary">
            <h1 class="text-5xl sm:text-6xl font-extrabold text-gray-900 mt-2 leading-tight">
                Hello, I’m Pranit! 👋
            </h1>
            <p class="mt-4 text-xl text-gray-700 font-medium max-w-2xl mx-auto">
                A <a href="https://github.com/kumarpranit" class="text-primary hover:text-primary-dark font-bold underline">Product Strategist</a> and a <a href="https://www.linkedin.com/in/kumarpranit/" class="text-primary hover:text-primary-dark font-bold underline">Data-Driven Decision Maker</a>
            </p>
        </header>

        <!-- DATA ANALYTICS PROJECTS SECTION -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-gray-900 mb-6 border-b-2 border-gray-200 pb-2">👨‍💻 Data Analytics Projects</h2>
            <div class="p-6 bg-white rounded-xl shadow-inner text-gray-600 border border-gray-100">
                <p>This is where your project summaries and links will go. Use this section to showcase your expertise in extracting insights from data.</p>
            </div>
        </section>

        <!-- PRODUCT MANAGEMENT INTERVIEWS SECTION -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-gray-900 mb-6 border-b-2 border-gray-200 pb-2">📺 Product Management Interviews</h2>
            <div class="p-6 bg-white rounded-xl shadow-inner text-gray-600 border border-gray-100">
                <p>List your media presence, interviews, or content here. This demonstrates communication and thought leadership.</p>
            </div>
        </section>

        <!-- CERTIFICATIONS SECTION -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-gray-900 mb-6 border-b-2 border-gray-200 pb-2 text-center">🏆 Core Certification Sample</h2>

            <!-- Certifications Grid (to center the single card) -->
            <div class="flex justify-center">

                <!-- Certification Card 1: Cloud Data Engineering (The main template) -->
                <div class="cert-card bg-white p-6 rounded-xl shadow-lg border border-gray-100 w-full max-w-md">
                    <div class="flex items-start space-x-4">
                        <!-- Icon Placeholder -->
                        <div class="cert-icon bg-indigo-100 text-indigo-700">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-database"><ellipse cx="12" cy="5" rx="9" ry="3"/><path d="M3 5V19A9 3 0 0 0 21 19V5"/><path d="M3 12h18"/><path d="M3 19h18"/></svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-gray-900">Google Cloud Professional Data Engineer</h3>
                            <p class="text-sm text-gray-500 mt-1">Issued by Google Cloud</p>
                        </div>
                    </div>
                    
                    <div class="mt-4 pt-4 border-t border-gray-100">
                        <p class="text-sm font-medium text-gray-700">Focus Areas:</p>
                        <ul class="text-gray-500 text-sm list-disc pl-5 mt-1 space-y-0.5">
                            <li>Designing Data Processing Systems</li>
                            <li>Building and Operating Data Pipelines</li>
                            <li>Security and Compliance</li>
                        </ul>
                    </div>
                    
                    <div class="mt-6 flex justify-between items-center">
                        <span class="text-sm font-semibold text-gray-500">
                            Completed: May 2023
                        </span>
                        <a href="https://www.credly.com/share/your-badge-id-1" target="_blank" class="px-4 py-2 bg-primary text-white text-sm font-medium rounded-lg hover:bg-primary-dark transition duration-150 shadow-md">
                            View Credential
                        </a>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Certifications Section -->

    </div>

</body>
</html>
