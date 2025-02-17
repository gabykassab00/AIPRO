<img src="./readme/Readme Template Assets//title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/Readme Template Assets/title2.svg"/>

>  A website for football academies that provides AI-powered analysis of uploaded gameplay clips. Coaches and players can use this platform to review their performance and identify areas for improvement.


### User Stories
#### Players

- As a player,I want to check individual player performance, so that I can understand my strengths and weaknesses.

- As a player,I want to receive detailed feedback from AI about the game,so that I can learn from my mistakes and improve my gameplay.

- As a player,I want to receive personalized training sets from AI based on my performance,so that I can effectively target areas for improvement.

#### Coaches

- As a coach,I want to check overall team performance,so that I can assess the team's strengths and weaknesses.

- As a coach,I want to get detailed feedback from AI about the game, so that I can identify areas for improvement for the team as a whole.

- As a coach,I want to receive AI-suggested sets of training for overall team improvement,so that I can effectively plan and conduct training sessions to address team needs.

<br><br>
<!-- Tech stack -->
<img src="./readme/Readme Template Assets/title3.svg"/>

###  AIPRO is built using the following technologies:

- This project uses the [Next.js](https://nextjs.org/) framework for the frontend. Next.js is a React-based web development framework that allows for server-side rendering, static site generation, and optimized performance for web applications.
- The backend is powered by [Django](https://www.djangoproject.com/), a high-level Python web framework known for its robustness and scalability. Django is used to handle API requests, manage user authentication, and orchestrate the AI-powered analysis workflows.
- For persistent storage, the project uses a [MySQL](https://www.mysql.com/) database. MySQL is a reliable and efficient relational database system that stores user data, gameplay analysis results, and training recommendations.
- The AI-driven analysis leverages advanced machine learning models to provide players and coaches with actionable insights, detailed game performance feedback, and personalized training recommendations for improvement.
- The platform follows modern design principles, ensuring an intuitive and user-friendly experience for both players and coaches.

<br><br>
<!-- UI UX -->
<img src="./readme/Readme Template Assets//title4.svg"/>


> We designed the football analysis platform using wireframes and mockups, iterating on the design until we achieved an intuitive layout that ensures seamless navigation and a user-friendly experience for players and coaches.

- Project Figma design [figma](https://www.figma.com/design/ZAy6TOinYUcO0aj3j9E5T0/Untitled?node-id=0-1&p=f&t=xAyXD9uoC30yY66z-0)


### Mockups
| Home screen  | Workflow Screen 
| ---| ---|
| ![Landing](./readme/demo/herofigma.png) | ![fsdaf](./readme/demo/workflw.png) | 

<br><br>
<!-- Database Design -->
<img src="./readme/Readme Template Assets/title5.svg"/>

###  Architecting Data Excellence: Innovative Database Design Strategies:

- <img src="./readme/public/db.png">


<br><br>

<!-- Implementation -->
<img src="./readme/Readme Template Assets/title6.svg"/>


### Admin Screens (Web)

| Normal Game      | Upload Game      |
| ----------------- | ---------------- |
| ![Landing](/readme/gif/before.gif)  | ![Login/Signup](/readme/gif/uploading.gif) |
| Analyzed Game    | Game Stats       |
| ![Landing](/readme/gif/after.gif)   | ![Login/Signup](/readme/gif/statsvideo.gif) |


> These are screenshots from the real Website.

| Login screen  | Register screen |  Home screen |
| ---| ---| ---|
| ![Landing](./readme/demo/login.png) | ![fsdaf](./readme/demo/register.png) | ![fsdaf](./readme/demo/home.png) |
| Workflow screen  | Updates Screen  | Clients Screen  |
| ![Landing](./readme/demo/workflow.png) | ![fsdaf](./readme/demo/update.png) | ![fsdaf](./readme/demo/clients.png) |
| Feedback screen  | Footer Screen  | Upload Screen  |
| ![Landing](./readme/demo/feedback.png) | ![fsdaf](./readme/demo/footer.png) | ![fsdaf](./readme/demo/upload.png) |
| Character screen  | Player Screen  | Team Screen  |
| ![Landing](./readme/demo/character.png) | ![fsdaf](./readme/demo/player.png) | ![fsdaf](./readme/demo/team.png) |
| Player Stats screen  | Coach Stats Screen  | Analyzer Screen  |
| ![Landing](./readme/demo/playerstats.png) | ![fsdaf](./readme/demo/coachstats.png) | ![fsdaf](./readme/demo/analyzer.png) |
| Program screen  | Video Screen  | Saved Stats Screen  |
| ![Landing](./readme/demo/program.png) | ![fsdaf](./readme/demo/video.png) | ![fsdaf](./readme/demo/saved.png) |

<br><br>
<img src="./readme/Readme Template Assets/title7.svg" id="installation"/>

### Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project leverages advanced prompt engineering techniques to optimize interactions with natural language processing models. The platform is powered by OpenAI's GPT-4, delivering personalized and contextually accurate feedback based on gameplay-specific data and AI-driven insights to help players and coaches improve their performance.

- To analyze uploaded gameplay clips, the platform integrates several advanced models and techniques. [YOLO](https://pjreddie.com/darknet/yolo/) is used as the AI object detection model to accurately track players and the ball throughout the game. [K-Means-Clustering](https://scikit-learn.org/1.5/modules/generated/sklearn.cluster.KMeans.html) is applied for pixel segmentation and clustering, enabling the identification of t-shirt colors to differentiate players and teams effectively. [Optical-Flow](https://www.mathworks.com/discovery/optical-flow.html#:~:text=What%20Is%20Optical%20Flow%3F,of%20objects%20in%20the%20video.) measures camera movement, ensuring stable and accurate gameplay analysis. Additionally, Perspective Transformation is utilized to adjust for field geometry and depth, providing precise positional data and an accurate representation of scene perspective. To further enhance the analysis, the platform calculates player speed and distance using Speed and Distance Calculation techniques, providing essential metrics for performance evaluation.

![Promts](./readme/demo/prompt.png)

<br><br>
<img src="./readme/Readme Template Assets/title10.svg" id="installation"/>


> This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
### Prerequisites

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=drive_link)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas


This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install 
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your Website. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/gabykassab00/AIPRO
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run Next.js app
   ```js
   npm run dev ;
   ```
4. Install Django
   ```js
   pip install django ;
   ```
5. Run Django
   ```js
   python manage.py runserver ;
   ```


