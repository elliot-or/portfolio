<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Welcome Page</title>
    <style>
      /* CSS Section */
      body {
        margin: 0;
        padding: 0;
        height: 100vh;
        background-color: #DEFFB8;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: Arial Black, Impact, sans-serif;
        overflow: hidden;
      }

      .welcome-container {
        text-align: center;
        position: relative;
        z-index: 1;
      }

      .welcome-text {
        color: #1e90ff;
        font-size: 4rem;
        letter-spacing: 2px;
        position: relative;
        text-transform: uppercase;
        display: block;
        margin: 0;
        line-height: 1.1;
      }
      
      .welcome-text:hover {
        transform: scale(4);
      }
      
      .falling-text {
        color: #fc585e;
        font-size: 3rem;
        letter-spacing: 2px;
        text-transform: uppercase;
        position: absolute;
        transform: translateX(-20%);
        opacity: 0;
        line-height: 1;
      }

      .aligned-position {
        transition: all 3s ease-out;
      }

      .door {
        position: absolute;
        bottom: 20px;
        right: 20px;
        width: 50px;
        height: 90px;
        background-color: #000;
        border-radius: 25px 25px 25px 25px;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
        z-index: 10;
        transition: transform 0.2s ease;
      }

      .door:hover {
        transform: scale(1.1);
      }

      .door-text {
        color: white;
        font-family: Arial Black, Impact, sans-serif;
        transform: rotate(78deg);
        letter-spacing: 2px;
        font-size: 1.8rem;
        text-align: center;
        text-transform: uppercase;
      }
    </style>
  </head>
  <body>
    <!-- HTML Section -->
    <div class="welcome-container">
      <h1 id="welcome-text-1" class="welcome-text">Welcoming</h1>
      <h1 id="welcome-text-2" class="welcome-text">All</h1>
    </div>
    <h1 id="falling-text-1" class="falling-text">To</h1>
    <h1 id="falling-text-2" class="falling-text">Free</h1>
    <h1 id="falling-text-3" class="falling-text">Fall</h1>
    <div class="door">
      <div class="door-text">Enter</div>
    </div>

    <!-- JavaScript Section -->
    <script>
      document.addEventListener("DOMContentLoaded", function () {
        // Get center text elements
        const welcomeText1 = document.getElementById("welcome-text-1");
        const welcomeText2 = document.getElementById("welcome-text-2");

        // Get falling text elements
        const fallingText1 = document.getElementById("falling-text-1");
        const fallingText2 = document.getElementById("falling-text-2");
        const fallingText3 = document.getElementById("falling-text-3");

        // Animation variables for center text elements
        let verticalPosition1 = 0;
        let horizontalPosition1 = 0;
        let verticalDirection1 = 1;
        let horizontalDirection1 = 1;

        let verticalPosition2 = 0;
        let horizontalPosition2 = 0;
        let verticalDirection2 = -1;
        let horizontalDirection2 = -1;

        // Variables for the falling text animations
        const fallingElements = [
          {
            element: fallingText1,
            position: -100,
            velocity: 0,
            rotation: Math.random() * 6 - 3,
            rotationSpeed: 0.05,
            bounceCount: 0,
            isResting: false,
            startDelay: 0,
            hasStarted: false,
            finalLeft: "32%",
          },
          {
            element: fallingText2,
            position: -100,
            velocity: 0,
            rotation: Math.random() * 6 - 3,
            rotationSpeed: 0.05,
            bounceCount: 0,
            isResting: false,
            startDelay: 100,
            hasStarted: false,
            finalLeft: "50%",
          },
          {
            element: fallingText3,
            position: -100,
            velocity: 0,
            rotation: Math.random() * 6 - 3,
            rotationSpeed: 0.05,
            bounceCount: 0,
            isResting: false,
            startDelay: 200,
            hasStarted: false,
            finalLeft: "70%",
          },
        ];

        // Physics constants
        const gravity = 0.02;
        const friction = 0.3;
        const maxBounces = 4;
        const rotationDamping = 0.02;

        // State variables
        let windowHeight, bottomEdge;
        let delayCounter = 0;
        let allElementsResting = false;
        let alignmentComplete = false;

        // Calculate screen dimensions
        function updateDimensions() {
          windowHeight = window.innerHeight;
          bottomEdge = windowHeight - 100;
        }

        // Calculate final position to align with door bottom
        function alignFinalText() {
          const door = document.querySelector(".door");
          const doorRect = door.getBoundingClientRect();
          const doorBottom = doorRect.bottom;

          fallingElements.forEach((item) => {
            item.element.classList.add("aligned-position");

            // Position the text so its bottom aligns with door bottom
            const finalBottom = windowHeight - doorBottom + -32; // Add 20px offset to move lower
            item.element.style.bottom = `${finalBottom}px`;
            item.element.style.top = "auto";
            item.element.style.left = item.finalLeft;
            item.element.style.transform = "translateX(-50%) rotate(0deg)";
          });

          alignmentComplete = true;
        }

        // Main animation function
        function animate() {
          // Animation for "WELCOMING" and "ALL"
          verticalPosition1 += 0.07 * verticalDirection1;
          if (verticalPosition1 >= 5 || verticalPosition1 <= -5) {
            verticalDirection1 *= -1;
          }

          horizontalPosition1 += 0.09 * horizontalDirection1;
          if (horizontalPosition1 >= 3 || horizontalPosition1 <= -3) {
            horizontalDirection1 *= -1;
          }

          verticalPosition2 += 0.08 * verticalDirection2;
          if (verticalPosition2 >= 6 || verticalPosition2 <= -6) {
            verticalDirection2 *= -1;
          }

          horizontalPosition2 += 0.1 * horizontalDirection2;
          if (horizontalPosition2 >= 4 || horizontalPosition2 <= -4) {
            horizontalDirection2 *= -1;
          }

          // Apply animations to welcome text
          welcomeText1.style.transform = `translateY(${verticalPosition1}px) translateX(${horizontalPosition1}px)`;
          welcomeText2.style.transform = `translateY(${verticalPosition2}px) translateX(${horizontalPosition2}px)`;

          // Increment counter for delayed starts
          delayCounter++;

          // Process each falling element
          let allResting = true;
          fallingElements.forEach((item, index) => {
            // Check if it's time to start this element
            if (!item.hasStarted && delayCounter >= item.startDelay) {
              item.element.style.opacity = 1;
              item.element.style.left = `${35 + index * 15}%`;
              item.hasStarted = true;
            }

            if (item.hasStarted && !alignmentComplete) {
              if (!item.isResting) {
                allResting = false;

                // Apply gentle gravity
                item.velocity += gravity;
                item.position += item.velocity;

                // Apply rotation during fall
                item.rotation += item.rotationSpeed;
                item.rotationSpeed *= 0.99;

                // Check for bounce at bottom
                if (item.position >= bottomEdge) {
                  item.position = bottomEdge;
                  // Bounce with dampening
                  item.velocity = -item.velocity * friction;
                  item.bounceCount++;

                  // Gentle rotation on impact
                  const impactForce = Math.abs(item.velocity);
                  const randomDirection = Math.random() > 0.5 ? 1 : -1;

                  // Apply gentle rotation
                  const bounceRotation = impactForce * 5 * randomDirection;
                  item.rotation += bounceRotation * 0.3;

                  // Add gentle rotational velocity
                  item.rotationSpeed = impactForce * 0.8 * randomDirection;

                  // Check for rest state
                  if (Math.abs(item.velocity) < 0.5) {
                    item.velocity = 0;
                    if (item.bounceCount >= maxBounces) {
                      item.isResting = true;
                    }
                  }
                }

                // Apply transform with rotation
                item.element.style.transform = `translateX(-50%) rotate(${item.rotation}deg)`;
                item.element.style.top = `${item.position}px`;
              } else {
                // Gradually level out to flat position
                const rotationDiff = 0 - item.rotation;
                item.rotation += rotationDiff * rotationDamping;

                // Apply the stabilizing rotation
                item.element.style.transform = `translateX(-50%) rotate(${item.rotation}deg)`;
              }
            }
          });

          // Check if all elements are at rest and alignment can begin
          if (allResting && !allElementsResting && !alignmentComplete) {
            allElementsResting = true;

            // Wait a moment before aligning
            setTimeout(alignFinalText, 800);
          }

          requestAnimationFrame(animate);
        }

        // Initialize
        updateDimensions();
        window.addEventListener("resize", updateDimensions);

        // Add click event to the door to navigate to a new page
        document.querySelector(".door").addEventListener("click", function () {
          window.location.href =
            "home.html"; // Replace with your destination page URL
        });

        animate();
      });
    </script>
  </body>
</html>
