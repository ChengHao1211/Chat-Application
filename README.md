# Chat-Application
ChatApp is a simple chat application built using MVVM architecture in C# .NET. It allows users to connect to a server and exchange messages with each other.

##Features
Connect to a server with a username.
Send messages to all connected users.
Receive messages from other users.
Get notified when users connect or disconnect.

##Prerequisites
Visual Studio (or any C# IDE)
.NET Framework

##Installation
1. Clone the repository:
git clone https://github.com/your_username/ChatApp.git

4. Open the solution file ChatApp.sln in Visual Studio.
5. Build the solution.
6. Run the application.

##Usage
1. Launch the application.
2. Enter your username and click "Connect."
3. Start sending messages in the chat window.

##Architecture
The application follows the MVVM (Model-View-ViewModel) architecture:

Model: Represents the data and business logic. (ChatApp.MVVM.Model)
View: Represents the UI components. (MainWindow.xaml)
ViewModel: Acts as an intermediary between the View and Model. (MainViewModel.cs)

##Dependencies
ChatApp.MVVM.Core: Contains the RelayCommand class, which is a basic implementation of the ICommand interface for MVVM.
ChatApp.NET: Handles client-side network communication.
ChatServer: Handles server-side logic and communication.

##Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.
