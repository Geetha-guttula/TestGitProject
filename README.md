# TestGitProject




News Article App (SwiftUI)

Project Description
The News Article App is a SwiftUI-based iOS application that fetches the latest news articles from NewsAPI and allows users to read, save, and manage articles. It follows best practices in SwiftUI development, including Core Data for local storage and WebKit for in-app browsing.

Features

1. API Integration
* Fetches news articles from NewsAPI.
* Displays article title, description, and image in a scrollable list.
2. Article Details
* Clicking on an article opens it in an in-app WebView using WebKit.
* A "Save" button allows users to store articles for offline access.
3. Local Database
* Uses Core Data for storing and retrieving saved articles.
* Saved articles can be accessed in a separate "Saved Articles" section.
* Users can delete saved articles.
4. UI/UX
* Built with SwiftUI’s modern UI components (List, NavigationStack, AsyncImage, etc.).
* Adaptive layout for a better user experience.


Added Bonus Features
* Offline Mode: Saved articles are available even without an internet connection.
* Dark Mode Support: The app adapts to system-wide dark mode.
* Share Button: Users can share articles via iOS ShareSheet.


Project Setup

1. Clone the repository from GitHub: git clone https://github.com/your-repo-link.git
2. cd NewsArticleApp
3. 
4. Open the project in Xcode.
5. Ensure you have a valid NewsAPI key and update the API URL in AppUrls.swift.
6. Build and run the app on a simulator or a real device.


Code Structure

ViewModels
* TabViewModel.swift: Manages selected tab state.
* NewsListViewModel.swift: Handles API calls, article fetching, and local storage interactions.

Networking
* ApiHandler.swift: Fetches news data from NewsAPI using URLSession.

Local Storage
* CoreData.swift: Implements Core Data methods for saving and fetching articles.

Views
* NewsListView.swift: Displays the list of news articles.
* NewsDetailView.swift: Shows the article inside a WebView with a save option.
* SavedArticlesView.swift: Displays saved articles.

Step-by-Step Implementation
1. Integrated NewsAPI to fetch news articles.
2. Designed UI using SwiftUI components like List, NavigationStack, and AsyncImage.
3. Implemented WebView to display full articles using WebKit.
4. Added Core Data to store and manage saved articles.
5. Developed ViewModels to manage business logic and API calls.
6. Created a Saved Articles Section to allow users to manage offline articles.
7. Enhanced UX by adding features like Dark Mode, article categorization, and sharing.


GitHub Repository Management
* Created the project repository in GitHub.
* Included detailed README.md for documentation.


Conclusion
This project showcases a well-structured SwiftUI application with API integration, local data storage, and modern UI/UX principles. It follows best practices and demonstrates expertise in Swift, Core Data, and networking.

