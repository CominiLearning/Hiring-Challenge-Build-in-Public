## **Your Challenge: Build Our First Interactive Activity**

For this challenge, you'll implement one of our planned activities: **The Balance Scale Addition Game**. This game teaches addition through visual intuition - imagine a balance scale where students need to find numbers that add up to match a target value. When they're close but not quite right, the scale tilts to show them if their sum is too large or too small!

This implementation will serve as a template for how we structure and build future activities.

## **Technical Requirements**

### **Frontend (Vue.js)**

1. **Authentication**
    - Integrate Firebase Authentication (email/password and Google sign-in)
    - Protected routes based on user roles
    - Session management
2. **Balance Game Interface**
    - Interactive balance scale visualization
    - Target number displayed on one side
    - Input fields for addends on the other
    - Visual feedback through scale tilt
    - Animations for balance states
    - Responsive design for different screen sizes
3. **Activity Builder**
    - Admin interface for creating other games
    - Configure difficulty levels
    - Set target ranges and number of addends
    - Preview functionality
    - Please see the expanded discussion below
4. **Technical Stack**
    - Vue Router for navigation
    - Pinia/Vuex for state management
    - Firestore for data persistence
    - CSS framework of your choice (Tailwind recommended)

### **Backend (FastAPI)**

1. **API Development**
    - Endpoints for game configuration
    - User progress tracking
    - Authentication token validation
2. **Data Management**
    - Game state schemas using Pydantic
    - Progress tracking
    - Error handling
    - Test coverage

## **Evaluation Criteria**

- Code organization and modularity
- Game mechanics implementation
- User experience and visual feedback
- Edge case handling
- Authentication implementation
- Documentation quality

## **Additional Challenges**

- Dockerize the application
- Add component unit tests
- **Design for Multiple Skill Levels:**
  - Create an intuitive interface for younger learners (think: visual cues, simpler numbers)
  - Scale difficulty for advanced students (multiple numbers, larger values, time challenges)
  - Build adaptive difficulty that responds to player performance
  - Consider adding visual themes or contexts that make addition more relatable (e.g., balancing weights, matching cookie quantities)

## **Why This Matters**

This balance scale game is just the beginning. Your implementation will help establish patterns for future activities like:

- Fraction visualization tools
- Geometry construction games
- Language learning exercises
- Science simulation activities

By building this foundation well, you'll help us create a platform that makes learning more intuitive and engaging for students worldwide.

## **Licensing**

This project is open source under the Apache License 2.0. This means:

- You can freely use and modify the code
- You can include it in commercial products
- You must include the original copyright notice
- You must state if you've made significant changes
- The original code maintainers have patent rights

Why this license? We want to build this in public and allow others to learn from and contribute to these educational tools, while ensuring we can sustainably maintain and develop the platform, including commercial applications.

You can find the full license in the LICENSE file of this repository.

## **Getting Started**

1. Fork the repository
2. Review the documentation
3. Set up your development environment
4. Create your project plan:
    - Break down the components
    - Set milestones
    - Identify potential challenges
    - Share your plan with us for feedback
5. Start building!

## **Documentation Expectations**

Your repository should include:

### **Project Plan**

Document your approach before diving in. What will you tackle first? How will you break this down into manageable pieces? We want to see your thought process.

### **Learning Journey**

Create a LEARNING.md in your repository. Use this to document:

- Technical challenges you faced
- How you solved them
- What you learned along the way
- Design decisions and their reasoning
- Things you'd do differently next time

Keep it real - we're interested in your authentic experience and growth through this project.

## **Important Note**

We value original thinking. While it's perfectly fine to use AI tools like ChatGPT to help with technical implementations or to explore ideas, we want to see _your_ critical thinking driving the project. Show us how you:

- Make architectural decisions
- Evaluate different approaches
- Solve problems creatively
- Learn from challenges

The best submissions we've seen aren't perfect, but they clearly show the developer's thought process and growth throughout the project.

Keep your repository private until we request otherwise, and reach out if you have questions!

## **Activity Builder (Expanded)**

An activity in our platform is any interactive learning experience with clear educational objectives. For the Balance Game, an activity consists of:

- A target number to match
- Input fields for addends
- Difficulty settings
- Success criteria
- Visual feedback rules

The Activity Builder interface should allow educators to:

- Create new games
- Set difficulty parameters:
  - Range of target numbers
  - Number of input fields
  - Time limits (optional)
  - Hints availability
- Define progression:
  - Starting difficulty
  - When to increase complexity
  - Success criteria to advance
- Preview and test configurations
- Save templates for reuse

For the Balance Game specifically, the builder should:

- Let educators create problem sets
- Configure visual feedback sensitivity
- Set appropriate number ranges for different age groups
- Define helpful messages for different types of wrong answers
- Create progression paths (e.g., start with 2 numbers, advance to 3)

This builder will serve as a template for future activities, demonstrating how we structure:

- Activity configuration
- Difficulty management
- Progress tracking
- Educational feedback

## **Licensing**
This project is open source under the Apache License 2.0. This means:

- You can freely use and modify the code
- You can include it in commercial products
- You must include the original copyright notice
- You must state if you've made significant changes
- The original code maintainers have patent rights

Why this license? We want to build this in public and allow others to learn from and contribute to these educational tools, while ensuring we can sustainably maintain and develop the platform, including commercial applications.

You can find the full license in the LICENSE file of this repository
