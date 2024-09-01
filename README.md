# **CalorieCrafter: Diet Planner**

**CalorieCrafter** is a Python-based diet planner application that utilizes the Tkinter library for its graphical user interface. It calculates daily caloric needs based on user input and provides meal suggestions to help users meet their dietary goals.

## **Features**

- **BMR Calculation**: Computes Basal Metabolic Rate (BMR) using the Harris-Benedict equation, customized for male and female users.
- **Personalized Meal Suggestions**: Provides breakfast, lunch, snacks, and dinner suggestions based on daily caloric needs.
- **Activity Level Adjustments**: Adjusts caloric requirements based on the user's activity level.

## **Installation**

1. Ensure you have Python installed on your system.
2. Download or clone the repository containing the script.

    ```bash
    git clone https://github.com/yourusername/CalorieCrafter.git
    ```

3. Navigate to the project directory.

    ```bash
    cd CalorieCrafter
    ```

4. Install any necessary dependencies (Tkinter comes pre-installed with Python, so no additional installation is typically needed).

## **Usage**

1. Run the application script.

    ```bash
    python dietician.py
    ```

2. Enter the required information:
    - **Weight**: Enter your weight in kilograms.
    - **Height**: Enter your height in centimeters.
    - **Age**: Enter your age in years.

3. Select your gender from the listbox.
4. Choose your activity level from the listbox.

5. Click the **Submit** button to calculate your daily caloric needs and get personalized meal suggestions.

## **Code Overview**

- **Imports**: The script imports `Tkinter` for the GUI and `randint` for generating random meal suggestions.
- **`BMR` Function**: Calculates daily caloric needs based on user input and displays meal suggestions based on calorie thresholds.
- **GUI Components**:
    - **Labels**: Used to display text and instructions.
    - **Entry Fields**: For user input of weight, height, and age.
    - **Listboxes**: For selecting gender and activity level.
    - **Button**: To trigger the BMR calculation and meal suggestion generation.

## **Example Output**

Depending on the calculated caloric needs, the application will provide different meal suggestions:

- For caloric needs below 1500:
  - Breakfast: Yogurt + Berries
  - Lunch: Cooked meat + Any vegetable + Leafy Greens + Cooked Grain + Olive oil
  - Snack: Soy nuts + Any vegetable
  - Dinner: Cooked fish + 2 Any vegetable + Leafy Greens + Oats + Grated Parmesan cheese
  - Snack: Banana

## **Contributing**

Feel free to submit issues or pull requests if you have improvements or bug fixes.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
