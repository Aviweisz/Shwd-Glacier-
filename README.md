# Shwd-Glacier- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schlam Family Glacier Itinerary '25</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .timeline-item {
            position: relative;
            padding-bottom: 2.5rem;
            padding-left: 2.5rem;
        }
        .timeline-item:last-child {
            padding-bottom: 0;
        }
        .timeline-marker {
            position: absolute;
            left: 0;
            top: 4px;
            width: 1rem;
            height: 1rem;
            border-radius: 9999px;
        }
        .timeline-line {
            position: absolute;
            left: 0.45rem;
            top: 1rem;
            bottom: 0;
            width: 2px;
        }
        .timeline-item:last-child .timeline-line {
            display: none;
        }
        .card {
            transition: box-shadow 0.3s ease-in-out;
        }
        .day-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .day-header {
            cursor: pointer;
        }
        .chevron-icon {
            transition: transform 0.3s ease-in-out;
        }
        .card.active .chevron-icon {
            transform: rotate(180deg);
        }

        /* Inspired by itineraries.com — Glacier Modern Refresh */
        body {
            background: linear-gradient(to bottom, #f7fafc 0%, #e2e8f0 100%);
            color: #2d3748;
            font-family: 'Plus Jakarta Sans', sans-serif;
        }

        .timeline-marker {
            background-color: #3182ce; /* bold sky blue */
        }

        .timeline-line {
            background-color: #cbd5e0;
        }

        .card {
            background-color: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 1rem;
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.05);
        }

        .card:hover {
            box-shadow: 0 20px 35px rgba(0, 0, 0, 0.08);
        }

        .day-header {
            background-color: #edf2f7;
            border-bottom: 1px solid #e2e8f0;
        }

        .chevron-icon {
            color: #3182ce;
        }

        h1, h2, h3, h4 {
            color: #2d3748;
        }

        .text-slate-800, .text-slate-900 {
            color: #2d3748 !important;
        }

        .text-slate-500 {
            color: #718096 !important;
        }

        .text-indigo-600, .text-indigo-800 {
            color: #3182ce !important;
        }

        .bg-indigo-50, .bg-indigo-100 {
            background-color: #ebf8ff !important;
        }

        .text-indigo-700 {
            color: #2c5282 !important;
        }

        .border-indigo-100, .border-indigo-500 {
            border-color: #63b3ed !important;
        }

        .hover\:bg-indigo-200:hover {
            background-color: #bee3f8 !important;
        }

        a {
            transition: color 0.2s ease-in-out;
        }

        a:hover {
            color: #2c5282;
        }
    </style>
</head>
<body class="text-gray-800">

    <div class="container mx-auto p-4 md:p-8 max-w-4xl">

        <!-- Header -->
        <header class="text-center mb-12 p-6">
            <h1 class="text-4xl md:text-5xl font-extrabold text-slate-900">Shwd Montana Itinerary </h1>
            <p class="text-2xl md:text-3xl text-indigo-600 mt-2 font-bold">Glacier Adventure </p>
            <p class="text-lg text-slate-500 mt-3">August 4 – 11, 2025</p>
        </header>

        <!-- Itinerary Days -->
        <div class="space-y-4" id="itinerary-accordion">

            <!-- Day 1: Monday, August 4 -->
            <div class="card overflow-hidden">
                <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 1: Arrival in Big Sky Country</h3>
                        <p class="text-md text-slate-500">Monday, August 4, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="relative border-t border-gray-200 pt-8">
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">5:29 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Arrival at FCA Airport</h4><p class="text-gray-600 mt-1">Welcome to Montana! Head to baggage claim and get ready to start your adventure.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">~6:15 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Pick Up Rental Cars</h4><p class="text-gray-600 mt-1">Thrifty Rental Car. Please have both reservation numbers ready.</p><div class="mt-2 space-x-2"><a href="https://view.emails.thrifty.com/?qs=76680a6cc57ecd028de0b8f439cff74fac319457c745a9c85f84cadafa2c3272ea714dfc183bcf647230de70848ff27c8caf19bd2ff439b03c7cd69d8f65d8dcf223126eabb537f11dad38618a503fd4" target="_blank" class="inline-block bg-indigo-100 text-indigo-800 text-sm font-semibold px-3 py-1 rounded-full hover:bg-indigo-200">Reservation #1</a><a href="https://view.emails.thrifty.com/?qs=76680a6cc57ecd028de0b8f439cff74fac319457c745a9c85f84cadafa2c3272ea714dfc183bcf647230de70848ff27c8caf19bd2ff439b03c7cd69d8f65d8dcf223126eabb537f11dad38618a503fd4" target="_blank" class="inline-block bg-indigo-100 text-indigo-800 text-sm font-semibold px-3 py-1 rounded-full hover:bg-indigo-200">Reservation #2</a></div></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">~7:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Check-in: The North Star Ranch</h4><p class="text-gray-600 mt-1">Address: <a href="https://www.google.com/maps/search/?api=1&query=355+Beaver+Lake+Rd" target="_blank" class="text-indigo-600 hover:underline font-medium">355 Beaver Lake Rd</a>. Settle in and explore your home for the week.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">8:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Welcome Dinner at the Ranch</h4><p class="text-gray-600 mt-1">Classic baby chicken cutlets on the grill with a side of grilled veggie skewers.</p></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 2: Tuesday, August 5 -->
            <div class="card overflow-hidden">
                <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 2: Going-to-the-Sun Road</h3>
                        <p class="text-md text-slate-500">Tuesday, August 5, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="relative border-t border-gray-200 pt-8">
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:30 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for Going-to-the-Sun Road</h4><p class="text-gray-600 mt-1">First stop: <a href="https://www.google.com/maps/place/Logan+Pass+Visitor+Center/@48.6953121,-113.7203295,17z/data=!3m2!4b1!5s0x5368af512bc4b521:0x815402de1f2424db!4m6!3m5!1s0x5368af512bf83b1f:0x64cdf1479b75bbbd!8m2!3d48.6953121!4d-113.7177546!16s%2Fm%2F04yfp25?entry=ttu&g_ep=EgoyMDI1MDcyMy4wIKXMDSoASAFQAw%3D%3D" target="_blank" class="text-indigo-600 hover:underline font-medium">Logan Pass Visitor Center</a>. Remember to bring your printed permits!</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">11:00 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Scenic Stops Along the Road</h4><p class="text-gray-600 mt-1">Take your time and enjoy the views. Stops include:</p><ul class="list-disc list-inside mt-2 text-gray-600"><li><a href="https://www.google.com/maps/search/?api=1&query=McDonald+Falls" target="_blank" class="text-indigo-600 hover:underline">McDonald Falls</a></li><li><a href="https://www.google.com/maps/search/?api=1&query=Red+Rock+Point+Glacier+National+Park" target="_blank" class="text-indigo-600 hover:underline">Red Rock Point</a></li><li><a href="https://www.google.com/maps/search/?api=1&query=The+Loop+Trailhead+Glacier+National+Park" target="_blank" class="text-indigo-600 hover:underline">The Loop Overlook</a></li><li><a href="https://www.google.com/maps/search/?api=1&query=Paradise+Meadow+Glacier+National+Park" target="_blank" class="text-indigo-600 hover:underline">Paradise Meadow</a></li></ul></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">1:30 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Hidden Lake Overlook Hike</h4><p class="text-gray-600 mt-1">A beautiful hike with rewarding views. Check the trail info for conditions.</p><a href="https://www.alltrails.com/trail/us/montana/hidden-lake-overlook" target="_blank" class="inline-block bg-indigo-100 text-indigo-800 text-sm font-semibold px-3 py-1 rounded-full hover:bg-indigo-200 mt-2">Trail Info</a></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">3:30 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for <a href="https://www.google.com/maps/place/Apgar,+MT+59936/@48.527744,-114.0034742,15z/data=!3m1!4b1!4m6!3m5!1s0x5366175c8f136cfd:0x192a64fd191df9fb!8m2!3d48.527745!4d-113.9931745!16s%2Fm%2F04b4d28?entry=ttu&g_ep=EgoyMDI1MDcyMy4wIKXMDSoASAFQAw%3D%3D" target="_blank" class="text-indigo-600 hover:underline">Apgar Village</a></h4><p class="text-gray-600 mt-1">Time to head to the west side of Lake McDonald.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">5:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Explore <a href="https://www.google.com/maps/place/Apgar,+MT+59936/@48.527744,-114.0034742,15z/data=!3m1!4b1!4m6!3m5!1s0x5366175c8f136cfd:0x192a64fd191df9fb!8m2!3d48.527745!4d-113.9931745!16s%2Fm%2F04b4d28?entry=ttu&g_ep=EgoyMDI1MDcyMy4wIKXMDSoASAFQAw%3D%3D" target="_blank" class="text-indigo-600 hover:underline">Apgar Village</a></h4><p class="text-gray-600 mt-1">Browse the shops, grab an ice cream, and enjoy the stunning lakeside views.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">7:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Lake McDonald Sunset Cruise & Dinner</h4><p class="text-gray-600 mt-1">Enjoy dinner on the water! Menu: Citrus salmon with a side of quinoa.</p><a href="https://www.google.com/maps/search/?api=1&query=Lake+McDonald+Lodge" target="_blank" class="text-indigo-600 hover:underline font-medium">Departs from Lake McDonald Lodge</a></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 3: Wednesday, August 6 -->
            <div class="card overflow-hidden">
                 <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 3: Hikes, Bikes & Dams</h3>
                        <p class="text-md text-slate-500">Wednesday, August 6, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="relative border-t border-gray-200 pt-8">
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:30 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for Avalanche Lake</h4><p class="text-gray-600 mt-1">Get ready for one of Glacier's most popular hikes.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">12:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Avalanche Lake Hike</h4><p class="text-gray-600 mt-1">Enjoy the walk through the Trail of the Cedars and up to the stunning lake.</p><a href="https://www.alltrails.com/trail/us/montana/avalanche-lake--6" target="_blank" class="inline-block bg-indigo-100 text-indigo-800 text-sm font-semibold px-3 py-1 rounded-full hover:bg-indigo-200 mt-2">Trail Info</a></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">4:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Biking / 2 Bridges (2 hours)</h4><p class="text-gray-600 mt-1">A leisurely bike ride to stretch your legs after the hike.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">6:30 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Visit Hungry Horse Dam</h4><p class="text-gray-600 mt-1">Marvel at the impressive engineering of one of the largest concrete arch dams in the US.</p><a href="https://www.usbr.gov/pn/hungryhorse/" target="_blank" class="inline-block bg-indigo-100 text-indigo-800 text-sm font-semibold px-3 py-1 rounded-full hover:bg-indigo-200 mt-2">Dam Info</a></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">7:30 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Dinner at the North Star Ranch</h4><p class="text-gray-600 mt-1">Rib steak with red wine reduction and a side of roasted asparagus.</p></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 4: Thursday, August 7 -->
            <div class="card overflow-hidden">
                 <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 4: Lakes, Bison & Rodeo</h3>
                        <p class="text-md text-slate-500">Thursday, August 7, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="relative border-t border-gray-200 pt-8">
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:00 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for Flathead Lake</h4><p class="text-gray-600 mt-1">Heading south to the largest freshwater lake west of the Mississippi.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">10:00 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Boat Tour on Flathead Lake</h4><p class="text-gray-600 mt-1">Departure Address: <a href="https://www.google.com/maps/search/?api=1&query=130+Bills+Rd" target="_blank" class="text-indigo-600 hover:underline font-medium">130 Bills Rd</a></p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">1:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for Bison Range</h4><p class="text-gray-600 mt-1">Address: <a href="https://www.google.com/maps/search/?api=1&query=58355+Bison+Range+Rd" target="_blank" class="text-indigo-600 hover:underline font-medium">58355 Bison Range Rd</a></p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">3:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Drive the Bison Range</h4><p class="text-gray-600 mt-1">Take the Prairie Drive and keep your eyes peeled for bison, elk, deer, and more! (Payment required on-site).</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">5:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Discover the Missoula County Fair</h4><p class="text-gray-600 mt-1">Experience a classic Montana county fair at the <a href="https://www.google.com/maps/search/?api=1&query=Clouse+Bauer+Arena" target="_blank" class="text-indigo-600 hover:underline font-medium">Clouse Bauer Arena</a>.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">6:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Dinner at the Fair</h4><p class="text-gray-600 mt-1">Chicken veggie stir fry & seasoned rice.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">7:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Rodeo Time!</h4><p class="text-gray-600 mt-1">Get ready for some thrilling rodeo action!</p><a href="https://missoulafairgrounds.com/events" target="_blank" class="inline-block bg-indigo-100 text-indigo-800 text-sm font-semibold px-3 py-1 rounded-full hover:bg-indigo-200 mt-2">Event Info</a></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart to the North Star Ranch</h4><p class="text-gray-600 mt-1">Time to head back after an action-packed day.</p></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 5: Friday, August 8 -->
            <div class="card overflow-hidden">
                <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 5: Rafting, Relaxation & Whitefish</h3>
                        <p class="text-md text-slate-500">Friday, August 8, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="relative border-t border-gray-200 pt-8">
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:00 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for River Rafting</h4><p class="text-gray-600 mt-1">Meeting Point: <a href="https://www.google.com/maps/search/?api=1&query=11900+US-2" target="_blank" class="text-indigo-600 hover:underline font-medium">11900 US-2</a></p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">10:00 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Private Boat Rafting Trip</h4><p class="text-gray-600 mt-1">Enjoy an exclusive trip down the river!</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">2:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Explore Downtown Whitefish</h4><p class="text-gray-600 mt-1">Discover the charming shops, galleries, and cafes of <a href="https://www.google.com/maps/search/?api=1&query=Whitefish+MT" target="_blank" class="text-indigo-600 hover:underline font-medium">Whitefish</a>.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">4:00 PM & 5:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Spa Time at The Lodge at Whitefish Lake</h4><p class="text-gray-600 mt-1">Time for some pampering and relaxation.</p><ul class="list-disc list-inside mt-2 text-gray-600"><li>Spa Group #1: 4:00 PM</li><li>Spa Group #2: 5:00 PM</li></ul></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">Optional</p><h4 class="font-bold text-lg mt-1 text-slate-800">Whitefish Ski Resort Scenic Chairlift</h4><p class="text-gray-600 mt-1">Take a ride up for breathtaking views of the valley. No reservations needed, starts at the Base Lodge.</p></div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Day 6: Saturday, August 9 -->
            <div class="card overflow-hidden">
                <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 6: Free Day</h3>
                        <p class="text-md text-slate-500">Saturday, August 9, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="border-t border-gray-200 pt-8">
                            <p class="text-gray-600">Today is a free day! Relax at the ranch, revisit a favorite spot, or explore something new. Enjoy the flexibility!</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 7: Sunday, August 10 -->
            <div class="card overflow-hidden">
                <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 7: East Glacier Adventure</h3>
                        <p class="text-md text-slate-500">Sunday, August 10, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="border-t border-gray-200 pt-8">
                            <div class="bg-indigo-50 border-l-4 border-indigo-500 p-4 rounded-r-lg mb-6"><h4 class="font-bold text-lg text-indigo-800">Choose Your Adventure!</h4><p class="text-indigo-700">Today you have a choice of activities.</p></div>
                            <div class="mb-6 border-2 border-indigo-100 p-4 rounded-lg"><h4 class="font-bold text-lg text-slate-800 mb-4">Option 1: St. Mary & Three Falls Hike</h4><div class="relative"><div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:30 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart to Rising Sun</h4><p class="text-gray-600 mt-1">Important: Go <span class="font-bold">around</span> Glacier, not through it. Destination: <a href="https://www.google.com/maps/search/?api=1&query=Rising+Sun+Boat+Dock" target="_blank" class="text-indigo-600 hover:underline font-medium">Rising Sun Boat Dock</a>.</p></div><div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">1:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">St. Mary Boat Shuttle</h4><p class="text-gray-600 mt-1">Enjoy the views from the boat as you cross St. Mary Lake.</p></div><div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">1:45 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Three Falls Hike</h4><p class="text-gray-600 mt-1">A beautiful hike to see Baring Falls, St. Mary Falls, and Virginia Falls.</p></div><div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">5:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart to Sacred Waters Brewery</h4><p class="text-gray-600 mt-1">Time for some local craft beer at <a href="https://www.google.com/maps/search/?api=1&query=Sacred+Waters+Brewing+Company" target="_blank" class="text-indigo-600 hover:underline font-medium">Sacred Waters Brewing Company</a>.</p></div><div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">7:00 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Live Music & Dinner</h4><p class="text-gray-600 mt-1">Enjoy live music at the brewery with a dinner of Baby Back Ribs.</p></div></div></div>
                            <div class="border-2 border-gray-200 p-4 rounded-lg"><h4 class="font-bold text-lg text-gray-800 mb-4">Option 2: Your Choice!</h4><p class="text-gray-600">This is a great alternative for those who prefer a different pace. Perhaps a relaxing day, more exploring in Whitefish, or another activity you discovered during the week.</p></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Day 8: Monday, August 11 -->
            <div class="card overflow-hidden">
                <div class="day-header p-6 flex justify-between items-center">
                    <div>
                        <h3 class="text-lg font-bold text-slate-800">Day 8: Homeward Bound</h3>
                        <p class="text-md text-slate-500">Monday, August 11, 2025</p>
                    </div>
                    <svg class="chevron-icon w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"></path></svg>
                </div>
                <div class="day-content">
                    <div class="px-6 pb-8">
                        <div class="relative border-t border-gray-200 pt-8">
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">Morning</p><h4 class="font-bold text-lg mt-1 text-slate-800">Pack Up & Grab To-Go Meals</h4><p class="text-gray-600 mt-1">Enjoy a final Montana morning. Make sure to pick up your packed lunch and dinner for the travel day.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:30 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Depart for FCA Airport</h4><p class="text-gray-600 mt-1">Time to head to <a href="https://www.google.com/maps/search/?api=1&query=Glacier+Park+International+Airport" target="_blank" class="text-indigo-600 hover:underline font-medium">Glacier Park International Airport</a>.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">10:15 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Return Rental Cars</h4><p class="text-gray-600 mt-1">Follow signs for rental car return at the airport.</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">11:59 AM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Take Off!</h4><p class="text-gray-600 mt-1">Delta Flight #3801 departs for JFK. Safe travels!</p></div>
                            <div class="timeline-item"><div class="timeline-marker"></div><div class="timeline-line"></div><p class="font-bold text-indigo-600">9:29 PM</p><h4 class="font-bold text-lg mt-1 text-slate-800">Land at JFK</h4><p class="text-gray-600 mt-1">Welcome home!</p></div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <script>
        // This script handles the accordion functionality for the itinerary.
        document.addEventListener('DOMContentLoaded', function () {
            const accordion = document.getElementById('itinerary-accordion');
            if (!accordion) return;
            const cards = accordion.querySelectorAll('.card');

            cards.forEach(card => {
                const header = card.querySelector('.day-header');
                const content = card.querySelector('.day-content');

                header.addEventListener('click', () => {
                    const isActive = card.classList.contains('active');

                    cards.forEach(otherCard => {
                        if (otherCard !== card) {
                            otherCard.classList.remove('active');
                            otherCard.querySelector('.day-content').style.maxHeight = null;
                        }
                    });

                    if (isActive) {
                        card.classList.remove('active');
                        content.style.maxHeight = null;
                    } else {
                        card.classList.add('active');
                        content.style.maxHeight = content.scrollHeight + 'px';
                    }
                });
            });
        });
    </script>

</body>
</html>
