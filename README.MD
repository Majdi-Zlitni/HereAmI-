# HereAmI

**HereAmI** is a .NET application designed to help users track the episodes they've watched along with the specific timestamps, across various streaming sites. This project aims to enhance the viewing experience by allowing users to resume exactly where they left off. The initial phase focuses on setting up user authentication and building a strong foundation for future site integrations.

---

## Features

- **Episode Tracking**: Record the episode and timestamp of your viewing progress.
- **User Authentication**: Secure login system to keep track of individual viewing data (JWT, OAuth, or other methods to be determined).
- **Future Streaming Site Support**: While initially focusing on a core set of functionality, the goal is to expand support to multiple streaming platforms.

---

## Installation

### Prerequisites

- **.NET** (version X.X)
- **Database** (SQL Server, SQLite, or another, as chosen)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HereAmI.git
   ```
2. Navigate to the project directory:
   ```bash
   cd HereAmI
   ```
3. Configure environment variables (e.g., database connection string, authentication keys).
4. Run the application:
   ```bash
   dotnet run
   ```

---

## Usage

- **Login/Register**: Create an account or log in to access your tracking dashboard.
- **Track Episodes**: Add episodes you watch, including timestamp data, and retrieve it whenever needed.

---

## Future Goals

- **Multi-Site Support**: Integration with various streaming platforms.
- **Enhanced Tracking**: Additional metadata options, such as episode ratings and notes.
- **Analytics**: Insights on viewing patterns and history.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any features or improvements.

---

## License

This project is licensed under the MIT License.
