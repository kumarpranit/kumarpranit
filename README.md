<h1>Hello, I’m Pranit! 👋</h1>
<p>
<h1>Hi, I'm Pranit! <br/><a href="https://github.com/kumarpranit">Product Strategist</a> and a <a href="https://www.linkedin.com/in/kumarpranit/">Data-Driven Decision Maker</a></h1>
</p>
<h2>👨‍💻 Data Analytics projects:</h2>

<h2>📺 Product Management Interviews </h2>

<h2> Certifications</h2>

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certification Showcase</title>
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

    <div class="max-w-6xl mx-auto">
        <!-- Section Header -->
        <header class="text-center mb-12">
            <h2 class="text-xs font-semibold uppercase tracking-widest text-secondary">
                Expertise Validated
            </h2>
            <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 mt-2">
                My Professional Certifications
            </h1>
            <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">
                Demonstrating mastery in Product Management, Data Analytics, and foundational technical domains.
            </p>
        </header>

        <!-- Certifications Grid -->
        <!-- Note: Changed grid layout to center a single item on smaller screens -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 max-w-xl mx-auto md:max-w-none">

            <!-- Certification Card 1: Cloud Data Engineering (The main template) -->
            <div class="cert-card bg-white p-6 rounded-xl shadow-lg border border-gray-100 md:col-span-3 lg:col-span-1 mx-auto w-full max-w-sm">
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
            
            <!-- Removed Card 2 and Card 3 for a minimal sample -->

        </div>
        <!-- End Certifications Grid -->

        <!-- Call to Action / Footer Note -->
        <div class="mt-12 text-center p-6 bg-primary-dark text-white rounded-xl shadow-xl">
            <p class="text-lg font-medium">
                Looking for more details? <a href="#" class="font-bold underline hover:text-secondary transition duration-150">Connect with me on LinkedIn</a> for my full professional background.
            </p>
        </div>

    </div>

</body>
</html>

