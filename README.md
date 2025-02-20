## **Your Challenge: Build Our First Interactive Activity**

For this challenge, you'll implement one of our planned activities: **The Balance Scale Addition Game**. This game teaches addition through visual intuition - imagine a balance scale where students need to find numbers that add up to match a target value. When they're close but not quite right, the scale tilts to show them if their sum is too large or too small!

This implementation will serve as a template for how we structure and build future activities.

>This is an excellent opportunity to showcase your skills while contributing to educational technology. All contributions will be publicly available, and any features or improvements that are incorporated into the project **will be credited to their creators**.

_Please make sur you read this in its entirety_. Understanding the requirements is an important aspect.

## But First, A Bit About Us

**Anyone can learn anything!**

We are [Comini Learning](https://www.comini.in/).

We truly believe this, and we are building an ecosystem of tools to help make it happen. Starting with early education, we're creating a new, **playful, personalized, and meaningful way of learning**.

Our approach combines both offline and online experiences:
- We run [microschools](https://www.comini.in/) that bring learning to life
- We develop online learning tools that adapt to each student
- We're building [learning copilots](https://tryripples.comini.in/) to support parents and educators

We realized that to enable personalized meaningful offline learning, we need to build our own full-stack of technology & AI tools that help with the philosophy (why), process (how), and practice (what) of learning. 

One of our key initiatives is [Zippie, our "microschool in a box"](https://www.youtube.com/watch?v=FqjGiSW8G_s) that integrates all these elements from the ground up.

You can read more about [our approach](https://blog.comini.in/p/how-can-we-personalize-learning) and [how we hire](https://saigaddam.medium.com/hiring-well-needs-systems-thinking-ce1ea4c45a09/).

Come help us build this ecosystem of tools and transform education for hundreds of millions!

**[Comini Learning](https://www.comini.in/) | [Our Blog](https://blog.comini.in/)**

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
    - **IMPORTANT**: Responsive design for different screen sizes, especially mobile. 
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

>This is an excellent opportunity to showcase your skills while contributing to educational technology. All contributions will be publicly available, and any features or improvements that are incorporated into the project **will be credited to their creators**.


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

You can find the full license in the LICENSE file of this repository.

## **Important Note About AI USAGE**
We are looking for evidence that you can think through/code different aspects of this problem. We want you to be able to think through ramifications and not just outsource it entirely to ChatGPT/LLMs. This is increasingly important as we find that many who are outsourcing programming to LLMs don't understand the code. This results in multiple issues — it is inefficient, has security vulnerabilities, unknown bugs, and more. This ultimately makes for a bad product too. So please be mindful and meaningful in its use.

## **Important Note About Responsive Design**
It is mentioned above, but worth reiterating. The game should be playable on mobile and desktop. Making learning activities accessible means designing for the most common screen sizes in India in home and classroom settings.
