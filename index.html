<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calorie & Nutrition Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #000000;
            color: #FFFFFF;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 2rem 1rem;
        }
        .container-main, .container-calculator {
            width: 100%;
            max-width: 56rem;
            background-color: #0A0A0A;
            border-radius: 1.5rem;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
            padding: 2.5rem;
            margin-bottom: 2rem;
            text-align: left;
        }
        .container-calculator {
            max-width: 40rem;
            text-align: center;
        }
        .gradient-text {
            background: linear-gradient(to right, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .section-header {
            text-align: center;
            font-weight: 800;
            margin-bottom: 1.5rem;
        }
        .form-label {
            display: block;
            text-align: left;
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: #E0E0E0;
        }
        .form-input, .form-select {
            width: 100%;
            padding: 0.75rem;
            border-radius: 0.75rem;
            border: 2px solid #444444;
            background-color: #1A1A1A;
            color: #FFFFFF;
            font-size: 1rem;
            outline: none;
            transition: border-color 0.2s ease;
        }
        .form-input:focus, .form-select:focus {
            border-color: #FFD700;
        }
        .submit-button {
            background-color: #FFD700;
            color: #000000;
            font-weight: 700;
            padding: 1rem 2.5rem;
            border-radius: 0.75rem;
            transition: all 0.2s ease;
            box-shadow: 0 8px 20px rgba(255, 215, 0, 0.3);
            font-size: 1.25rem;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            width: 100%;
        }
        .submit-button:hover {
            background-color: #FFA500;
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(255, 215, 0, 0.4);
        }
        #calculator-results {
            display: none;
            text-align: left;
            margin-top: 2rem;
            padding: 1.5rem;
            background-color: #1A1A1A;
            border-radius: 1rem;
            border: 2px solid #444444;
        }
        .result-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0.75rem 0;
            border-bottom: 1px solid #333333;
        }
        .result-item:last-child {
            border-bottom: none;
        }
        .result-value {
            font-weight: 700;
            color: #FFD700;
        }
        .unit-toggle {
            display: inline-flex;
            border-radius: 9999px;
            background-color: #1A1A1A;
            padding: 0.25rem;
            margin-left: 1rem;
        }
        .unit-toggle-btn {
            padding: 0.5rem 1rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            font-weight: 500;
            cursor: pointer;
            transition: background-color 0.2s;
        }
        .unit-toggle-btn.active {
            background-color: #444444;
            color: #FFD700;
        }
        .input-group {
            display: flex;
            align-items: center;
            margin-top: 0.5rem;
        }
        .input-group .form-input {
            margin-right: 0.5rem;
        }
        .card {
            background-color: #1A1A1A;
            border-radius: 1rem;
            padding: 1.5rem;
            border: 2px solid #333333;
            margin-top: 1.5rem;
        }
        .diet-plan-card {
            background-color: #1A1A1A;
            border-radius: 1rem;
            padding: 1.5rem;
            border: 2px solid #333333;
            margin: 0.5rem;
        }
        .accent-link {
            color: #FFD700;
            font-weight: 600;
            transition: color 0.2s;
        }
        .accent-link:hover {
            color: #FFA500;
        }
        #loading-indicator {
            display: none;
            text-align: center;
            margin-top: 1rem;
            color: #FFD700;
        }
        .meal-plan-container {
            display: none;
            margin-top: 2rem;
        }
        .meal-plan-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1rem;
        }
        .meal-item {
            margin-bottom: 1rem;
        }
        .meal-item h3 {
            font-size: 1.25rem;
            font-weight: 600;
            color: #FFD700;
            margin-bottom: 0.5rem;
        }
        .meal-item ul {
            list-style-type: none; /* Remove default bullets */
            padding-left: 0;
            color: #E0E0E0;
        }
        .meal-item li {
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        .meal-image {
            width: 50px;
            height: 50px;
            border-radius: 0.5rem;
            border: 1px solid #444444;
            object-fit: cover;
            flex-shrink: 0; /* Prevents the image from shrinking */
        }
        
        /* Blinking animation for loading indicator */
        @keyframes blink {
            0% { opacity: 0; }
            50% { opacity: 1; }
            100% { opacity: 0; }
        }

        .blinking {
            animation: blink 1.5s infinite;
        }
    </style>
</head>
<body>
    <!-- Advanced Calorie & Macro Calculator Section -->
    <div id="calorie-calculator-section" class="container-calculator w-full">
        <h1 class="text-3xl sm:text-4xl font-extrabold leading-tight mb-4 gradient-text">
            Advanced Calorie & Macro Calculator
        </h1>
        <p class="text-base sm:text-lg text-gray-400 mb-8">
            Find out your daily caloric needs and macronutrient breakdown to crush your fitness goals.
        </p>

        <form id="calculator-form" class="space-y-6">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                    <label for="age" class="form-label">Age (years)</label>
                    <input type="number" id="age" name="age" required class="form-input" min="1" max="120">
                </div>
                <div>
                    <label for="gender" class="form-label">Gender</label>
                    <select id="gender" name="gender" required class="form-select">
                        <option value="male">Male</option>
                        <option value="female">Female</option>
                    </select>
                </div>
                <div>
                    <label for="height" class="form-label">Height</label>
                    <div class="input-group">
                        <input type="number" id="height" name="height" required class="form-input" min="1" max="300">
                        <div class="unit-toggle">
                            <span id="height-cm" class="unit-toggle-btn active" data-unit="cm">cm</span>
                            <span id="height-in" class="unit-toggle-btn" data-unit="in">in</span>
                        </div>
                    </div>
                </div>
                <div>
                    <label for="weight" class="form-label">Weight</label>
                    <div class="input-group">
                        <input type="number" id="weight" name="weight" required class="form-input" min="1" max="500">
                        <div class="unit-toggle">
                            <span id="weight-kg" class="unit-toggle-btn active" data-unit="kg">kg</span>
                            <span id="weight-lb" class="unit-toggle-btn" data-unit="in">lb</span>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <label for="activity" class="form-label">Activity Level</label>
                <select id="activity" name="activity" required class="form-select">
                    <option value="1.2">Sedentary (little or no exercise)</option>
                    <option value="1.375">Lightly Active (light exercise/sports 1-3 days/week)</option>
                    <option value="1.55">Moderately Active (moderate exercise/sports 3-5 days/week)</option>
                    <option value="1.725">Very Active (hard exercise/sports 6-7 days/week)</option>
                    <option value="1.9">Extremely Active (hard daily exercise/physical job)</option>
                </select>
            </div>
            <div>
                <label for="goal" class="form-label">Goal</label>
                <select id="goal" name="goal" required class="form-select">
                    <option value="loss">Weight Loss</option>
                    <option value="maintain">Maintenance</option>
                    <option value="gain">Weight Gain</option>
                </select>
            </div>
            <div>
                <label for="diet" class="form-label">Dietary Preference</label>
                <select id="diet" name="diet" required class="form-select">
                    <option value="Paleo">Paleo</option>
                    <option value="Vegan">Vegan</option>
                    <option value="Carnivore">Carnivore</option>
                </select>
            </div>
            <div>
                <button type="submit" class="submit-button">
                    Calculate & Get My Plans
                </button>
            </div>
        </form>

        <div id="calculator-results">
            <h3 class="text-2xl font-bold mb-4 text-center gradient-text">Your Personalized Results</h3>
            <div class="result-item">
                <span class="text-gray-300">Daily Calories:</span>
                <span id="calorie-result" class="result-value"></span>
            </div>
            <div class="mt-6 mb-2 text-center text-lg font-bold text-gray-300">Macronutrient Breakdown</div>
            <div class="result-item">
                <span class="text-gray-300">Protein:</span>
                <span id="protein-result" class="result-value"></span>
            </div>
            <div class="result-item">
                <span class="text-gray-300">Carbohydrates:</span>
                <span id="carbs-result" class="result-value"></span>
            </div>
            <div class="result-item">
                <span class="text-gray-300">Fats:</span>
                <span id="fats-result" class="result-value"></span>
            </div>
        </div>
    </div>

    <!-- New Section: AI-Powered Meal Plans -->
    <div class="container-main w-full">
        <h1 class="text-4xl sm:text-5xl section-header gradient-text">
            Your AI-Powered Nutrition Guide
        </h1>
        <p class="text-lg text-gray-300 mb-8 text-center">
            Discover a variety of personalized meal plans generated by AI to match your goals.
        </p>

        <section class="mb-10">
            <h2 class="text-3xl section-header gradient-text">AI Generation</h2>
            <div id="loading-indicator" class="text-center" style="display: none;">
                <div class="flex flex-col items-center justify-center">
                    <div class="flex items-center">
                        <svg class="animate-spin -ml-1 mr-3 h-5 w-5 text-yellow-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                            <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
                            <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                        </svg>
                        <span class="text-xl sm:text-2xl font-bold blinking">Generating your content...</span>
                    </div>
                    <p class="mt-2 text-sm text-gray-400">Usually takes 15-30 seconds, please be patient.</p>
                </div>
            </div>
            <div id="content-container" class="mt-6">
                <!-- Generated content will be injected here -->
            </div>
        </section>
        
        <p class="text-sm text-gray-500 text-center mt-8">
            Disclaimer: This information is for educational purposes only. Please consult a healthcare professional before making any significant changes to your diet. The meal plans and images are AI-generated and are intended as visual guides.
        </p>
    </div>

    <script>
        // --- CALORIE & MACRO CALCULATOR LOGIC ---
        const form = document.getElementById('calculator-form');
        const calculatorResultsDiv = document.getElementById('calculator-results');
        const heightUnitBtns = document.querySelectorAll('#height .unit-toggle-btn');
        const weightUnitBtns = document.querySelectorAll('#weight .unit-toggle-btn');
        const heightInput = document.getElementById('height');
        const weightInput = document.getElementById('weight');
        const loadingIndicator = document.getElementById('loading-indicator');
        const contentContainer = document.getElementById('content-container');
        
        let heightUnit = 'cm';
        let weightUnit = 'kg';

        // Event listeners for unit toggles
        heightUnitBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                heightUnitBtns.forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                heightUnit = btn.dataset.unit;
            });
        });

        weightUnitBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                weightUnitBtns.forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                weightUnit = btn.dataset.unit;
            });
        });

        form.addEventListener('submit', async (e) => {
            e.preventDefault();

            const age = parseInt(document.getElementById('age').value);
            const gender = document.getElementById('gender').value;
            let height = parseFloat(heightInput.value);
            let weight = parseFloat(weightInput.value);
            const activityLevel = parseFloat(document.getElementById('activity').value);
            const goal = document.getElementById('goal').value;
            const dietType = document.getElementById('diet').value;

            // Convert units to metric for calculation
            if (heightUnit === 'in') {
                height *= 2.54; // inches to cm
            }
            if (weightUnit === 'lb') {
                weight /= 2.20462; // lbs to kg
            }

            let bmr;
            if (gender === 'male') {
                bmr = (10 * weight) + (6.25 * height) - (5 * age) + 5;
            } else {
                bmr = (10 * weight) + (6.25 * height) - (5 * age) - 161;
            }

            let tdee = bmr * activityLevel;
            let finalCalories = tdee;

            if (goal === 'loss') {
                finalCalories -= 500;
            } else if (goal === 'gain') {
                finalCalories += 500;
            }
            finalCalories = Math.round(finalCalories);

            const proteinGrams = Math.round((finalCalories * 0.3) / 4);
            const carbsGrams = Math.round((finalCalories * 0.4) / 4);
            const fatsGrams = Math.round((finalCalories * 0.3) / 9);

            document.getElementById('calorie-result').textContent = `${finalCalories} kcal`;
            document.getElementById('protein-result').textContent = `${proteinGrams} g`;
            document.getElementById('carbs-result').textContent = `${carbsGrams} g`;
            document.getElementById('fats-result').textContent = `${fatsGrams} g`;

            calculatorResultsDiv.style.display = 'block';
            calculatorResultsDiv.scrollIntoView({ behavior: 'smooth' });

            // --- AI-POWERED CONTENT GENERATION ---
            await generateAIContent(dietType, finalCalories, proteinGrams, carbsGrams, fatsGrams);
        });

        // Exponential backoff for API calls
        async function fetchWithRetry(url, options, maxRetries = 5, delay = 1000) {
            for (let i = 0; i < maxRetries; i++) {
                try {
                    const response = await fetch(url, options);
                    if (response.status !== 429) { // Not a rate limit error, proceed
                        return response;
                    }
                } catch (error) {
                    console.error('Fetch failed, retrying...', error);
                }
                await new Promise(res => setTimeout(res, delay * Math.pow(2, i)));
            }
            throw new Error('Max retries exceeded');
        }

        async function generateAIContent(dietType, calorieGoal, proteinGrams, carbsGrams, fatsGrams) {
            loadingIndicator.style.display = 'block';
            contentContainer.innerHTML = '';
            
            const apiKey = "";
            const textApiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;
            const imageApiUrl = `https://generativelanguage.googleapis.com/v1beta/models/imagen-3.0-generate-002:predict?key=${apiKey}`;

            // Original logic for diet types
            const textPrompt = `Generate a 3-meal plan (Breakfast, Lunch, Dinner) for a ${dietType} diet, targeting approximately ${calorieGoal} calories. If the diet is "Carnivore", make sure to mention or include biltong or droëwors as a meal or snack. The meal ideas should be based on ingredients you could easily find at South African stores like Checkers or Woolworths. Be specific with food items and portion sizes. For each meal item, provide a brief, descriptive phrase suitable for an image generation model. Format the response as a JSON object with the following structure: 
            {
                "diet_name": "${dietType}",
                "meals": [
                    {
                        "meal_name": "Breakfast",
                        "items": [
                            {"description": "...", "image_prompt": "a stylized drawing of ..."},
                            ...
                        ]
                    },
                    ...
                ]
            }
            The descriptions should be detailed and the image prompts should be concise and visual.`;

            const textPayload = {
                contents: [{ parts: [{ text: textPrompt }] }],
                generationConfig: { responseMimeType: "application/json" }
            };

            let mealPlanData;
            try {
                const textResponse = await fetchWithRetry(textApiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(textPayload)
                });
                const textResult = await textResponse.json();
                mealPlanData = JSON.parse(textResult.candidates[0].content.parts[0].text);
            } catch (e) {
                console.error('Failed to parse JSON from AI:', e);
                mealPlanData = {
                    diet_name: dietType,
                    meals: [{
                        meal_name: "Error",
                        items: [{ description: "Could not generate a meal plan. Please try again.", image_prompt: "a question mark" }]
                    }]
                };
            }

            // Generate and display the meal plan card
            const dietCard = document.createElement('div');
            dietCard.className = 'diet-plan-card';
            dietCard.innerHTML = `<h2 class="text-2xl font-bold mb-4 gradient-text text-center">${mealPlanData.diet_name} Diet Plan</h2><div class="meal-plan-grid"></div>`;
            const mealPlanGrid = dietCard.querySelector('.meal-plan-grid');

            for (const meal of mealPlanData.meals) {
                const mealSection = document.createElement('div');
                mealSection.className = 'meal-item';
                mealSection.innerHTML = `<h3>${meal.meal_name}:</h3><ul></ul>`;
                const ul = mealSection.querySelector('ul');

                for (const item of meal.items) {
                    const li = document.createElement('li');
                    li.innerHTML = `
                        <img src="https://placehold.co/50x50/333/000?text=Loading" alt="Loading image" class="meal-image">
                        <span>${item.description}</span>
                    `;
                    ul.appendChild(li);

                    // Generate image for each item using Imagen API
                    const imagePrompt = `a small, top-down view of ${item.image_prompt}`;
                    const imagePayload = {
                        instances: { prompt: imagePrompt },
                        parameters: { "sampleCount": 1 }
                    };

                    const imageResponse = await fetchWithRetry(imageApiUrl, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(imagePayload)
                    });

                    const imageResult = await imageResponse.json();
                    if (imageResult.predictions && imageResult.predictions.length > 0 && imageResult.predictions[0].bytesBase64Encoded) {
                        const imageUrl = `data:image/png;base64,${imageResult.predictions[0].bytesBase64Encoded}`;
                        const imgElement = li.querySelector('img');
                        imgElement.src = imageUrl;
                        imgElement.alt = item.image_prompt;
                    } else {
                        console.error('Failed to generate image for prompt:', imagePrompt);
                    }
                }
                mealPlanGrid.appendChild(mealSection);
            }
            contentContainer.appendChild(dietCard);
            loadingIndicator.style.display = 'none';
        }
    </script>
</body>
</html>
