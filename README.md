## AWS Flip & Pair Game 🎴🚀
  A fun and interactive memory-based card matching game where players flip cards and try to find matching pairs! Test your memory skills and beat the clock. Suitable for players of all ages.😉

## Game Features 🎮
- **Exciting Gameplay:** Flip and match cards while sharpening your memory.
- **Dynamic Timer:** Race against time to complete the challenge.
- **User-Friendly Interface:** Easy navigation with smooth animations.
- **Interactive Fun:** Suitable for players of all skill levels.

## How to Play 🕹️
1. Start the game by clicking **"Start Game"**.
2. Flip two cards by clicking on them.
3. If the cards match, they stay flipped. If not, they flip back.
4. Match all pairs before the time runs out to win!


## Continuous Deployment using AWS Code Pipeline and S3 ⚙️☁️
The game leverages AWS services for seamless deployment and hosting. Here’s how it works:

1. **S3 Bucket Hosting:**<br/>
    • Create an S3 bucket to host the game as a static website.<br/>
    • Set proper permissions to allow public access to the game files.

2. **AWS CodePipeline:**<br/>
    • Automate your deployment process.<br/>
    • The pipeline pulls code from your GitHub repository and deploys it to the S3 bucket whenever changes are      detected.

3. **End-to-End Workflow:**<br/>
    • Modify your code on GitHub → The pipeline detects the change → Updates are deployed to S3 automatically.

## The Deployment Environment 🚀
- **Hosting:** The game is deployed and hosted on an S3 bucket for scalability and speed.
- **Automation:** Continuous deployment is set up using AWS CodePipeline for efficient updates.

## The Deployment Pipeline 🚀
The pipeline is created using AWS Code Pipeline.  The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.

## Technologies Used 🛠️
**Frontend:** HTML, CSS, JavaScript  
**AWS Services:** S3, CodePipeline  
**Version Control:** GitHub  

## Cost 💰
- The game utilizes AWS Free Tier eligible services, ensuring low-cost deployment during development.
- **Important:** Charges may occur if the Free Tier limits are exceeded. It’s recommended to monitor your usage and shut down resources when not in use.

## 🤝 Contributions
You are welcomed! for any contributions, or suggestions. Any useful updation of code, or modification in a file is expected as a piece of contribution.

**Steps for contributions:**
1. ⭐ Star this repository.
2. Fork and Clone
3. Make an appropriate PR, and describing your changes in a systematic format.

## Acknowledgements 🙌
Thanks to AWS for providing robust cloud services for hosting and deployment.
Inspired by the love for simple, engaging memory games.