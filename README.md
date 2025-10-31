### Workflow for Generating UI via Generative AI Coding Tools

This workflow outlines a step-by-step process for recreating and iterating on UI designs using AI tools, starting from a screenshot and progressing to advanced features and extensions. It emphasizes high-fidelity recreation, personalization, and integration with other tools.

1. **Initial Recreation from Screenshot**  
   Provide a screenshot to the AI with the prompt: "Help me rebuild this UI in a pixel-perfect manner in a single HTML file."  
   - Include details on colors, formatting, and style to convey the overall feel.  
   - This establishes high-fidelity context for the AI.

2. **Refined UI Generation**  
   Use the same screenshot, but focus solely on UI generation to recreate a single page.  
   - Apply the same prompt as Step 1, but include extracted CSS for greater accuracy.

3. **Error Correction**  
   Review and correct any mistakes in the generated UI using VisBug (a tool for quickly inspecting and editing UI elements).

4. **Personalization Iteration**  
   Iterate on the UI to incorporate a more personalized style, refining based on feedback or preferences.

5. **Style Guide Generation**  
   Create a detailed style guide prompt (refer to `style-guide.md` for examples or templates).

6. **Build New UI Based on Style Guide**  
   Use the `/ui-design` command to generate a new UI interface, incorporating the style guide from Step 5.

7. **Feature Expansion**  
   Once the base UI is solidified, add new features to the design.

8. **Animation Extensions**  
   Enhance the UI with animations:  
   - Use Framer Motion to create product demo animations incorporating real components.  
   - Alternatively, apply Framer Motion for general application animations.

9. **Mobile App Integration**  
   Copy the style guide and reference HTML page into Google Stitch to design screens for a mobile app.
