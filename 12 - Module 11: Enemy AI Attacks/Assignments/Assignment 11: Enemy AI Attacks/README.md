# Assignment 11: Enemy AI Attacks

<h3>Assignment: Advanced AI Development in Unreal Engine 5</h3>
<h4>Objective:</h4>
<p>Apply the principles learned in the lesson to enhance the AI of a base enemy character in Unreal Engine 5. This involves refactoring the existing AI code for optimization, creating a Behavior Tree service to manage attack range, implementing this service within a behavior tree, and developing a patrolling behavior for the enemy.</p>
<h4>Tasks:</h4>
<ol>
<li>
<p><strong>Refactor Base Enemy AI Code:</strong></p>
<ul>
<li>Review the current AI code for your base enemy character. Identify areas for improvement, such as redundant code, lack of efficiency, or poor readability.</li>
<li>Refactor the code to optimize performance and maintainability. Ensure your changes do not affect the existing functionality negatively.</li>
</ul>
</li>
<li>
<p><strong>Create a Behavior Tree Service for Attack Range:</strong></p>
<ul>
<li>Develop a new Behavior Tree service in UE5 that determines whether the player is within a specified attack range of the enemy.</li>
<li>Use blackboard variables to store and communicate the attack range status to other parts of the Behavior Tree.</li>
</ul>
</li>
<li>
<p><strong>Implement the Attack Range Service:</strong></p>
<ul>
<li>Integrate your newly created attack range service into the enemy's Behavior Tree.</li>
<li>Adjust the enemy's behavior to attack the player when within range and revert to other behaviors (e.g., patrolling) when the player is out of range.</li>
</ul>
</li>
<li>
<p><strong>Develop Patrolling Behavior:</strong></p>
<ul>
<li>Create a series of waypoints in your game level for the enemy to patrol between.</li>
<li>Implement logic within the Behavior Tree that allows the enemy to move between these waypoints in a loop when not engaged in combat or pursuing the player.</li>
</ul>
</li>
</ol>
<h4>Deliverables:</h4>
<ol>
<li>
<p><strong>Refactored AI Code:</strong></p>
<ul>
<li>Submit the updated AI code for your base enemy character. Include comments explaining the changes you made and why.</li>
</ul>
</li>
<li>
<p><strong>Behavior Tree and Service Implementation:</strong></p>
<ul>
<li>Provide screenshots or a short video demonstrating the attack range service within the Behavior Tree editor, highlighting how it integrates with the enemy's overall behavior.</li>
</ul>
</li>
<li>
<p><strong>Demonstration Video:</strong></p>
<ul>
<li>Record a 2-3 minute video showcasing the enhanced enemy AI in action. This should include clips of the enemy patrolling, detecting the player's attack range, and engaging in combat.</li>
</ul>
</li>
</ol>
<p>You will upload screenshots of your code and updates along with video of your functioning AI enemies</p>