# ContributorTaskManager

A Java-based tool designed to optimize task assignment for contributors based on their skill levels and task difficulty.



## Logic Of Problem

In collaborative projects, efficiently assigning tasks to contributors based on their skill levels ensures optimal productivity. Without proper task assignment, tasks may remain uncompleted, leading to bottlenecks and delayed project progress.

## Solution

The Contributor Task Manager utilizes sorting algorithms to match contributors with tasks based on their skill levels and task difficulties. The project leverages Java and AWS Cloud services like EC2, S3, and CloudFront for scalable deployment.

## Features

- **Task Assignment Logic**: Assigns tasks based on contributor skill levels and task difficulty.
- **Dynamic Task Sorting**: Prioritizes high-difficulty tasks for higher-skilled contributors.
- **Unassigned Task Handling**: Ensures tasks are not left unattended if contributors lack sufficient skills.



## Technologies Used
- **Java**: Core language for implementing the logic.  
- **AWS EC2, S3, CloudFront**: For cloud-based deployment and scalable architecture.  
- **Cloudflare**: For optimizing DNS and SSL configurations.  



## How to Run
1. Clone the repository:  
   ```bash  
   git clone https://github.com/username/contributor-task-manager.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd contributor-task-manager  
   ```  
3. Compile the Java file:  
   ```bash  
   javac ContributorTaskManager.java  
   ```  
4. Run the project:  
   ```bash  
   java ContributorTaskManager  
   ```



## Output
Contributor: Alice  
  - Optimize Database Queries (Difficulty: 5)  
  - Design User Interface (Difficulty: 4)  
Contributor: Bob  
  - Build API Endpoint (Difficulty: 3)  
Contributor: Charlie  
  - Write Unit Tests (Difficulty: 2)  


## Challenges & Solutions  
- **Media Upload Issue**: Contributors were unable to upload media files to S3 due to missing permissions.  
  - **Solution**: Configured S3 bucket permissions with `public-read` access and ensured the `wp-config.php` file included S3 configuration.  


## Future Improvements
- Enhance the task assignment algorithm to consider workload balancing.
- Add analytics or monitoring to track task completion and contributor performance.

## Project Repository  

[GitHub Repository](https://github.com/KashishV2/ContributorTaskManager.git)  

## Contribution Guidelines  
Contributions are welcome!  
1. Fork this repository.  
2. Create a new branch:  
   ```bash  
   git checkout -b feature-branch  
   ```  
3. Make changes and submit a pull request.


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/kashish-varshney-166333273/)
[![GitHub](https://img.shields.io/badge/GitHub-1DA152?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KashishV2/)

