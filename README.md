# 🌍 Earthquake Tracker App

## 📖 Description

The **Earthquake Tracker App** is a real-time earthquake monitoring application built using **Flutter**. It utilizes the **USGS Earthquake API** to fetch real-time data on earthquakes happening worldwide. Users can select a specific date range to view earthquakes within that period, including details such as magnitude, location, time, and severity levels represented by different colors. The app also supports both **light mode** and **dark mode** for enhanced user experience.

## 🛠️ Tech Stack & Packages Used

- **Flutter**: Frontend framework for building the application.
- **USGS Earthquake API**: For fetching real-time earthquake data.
- **Provider**: State management solution for managing app-wide state.
- **HTTP**: For making API requests.
- **Geolocator**: For fetching user location.
- **Geocoding**: To convert latitude and longitude into readable location names.

## ✨ Features

✅ **Real-time Earthquake Data** - Fetches real-time earthquake data from USGS.

✅ **Date-based Filtering** - Users can select a start date and end date to view past earthquake data.

✅ **Detailed Earthquake Info** - Displays magnitude, time, location, and severity.

✅ **Danger Level Indication** - Uses **Red** (high risk) and **Green** (low risk) colors for severity indication.

✅ **Dark Mode Support** - Seamlessly switch between light and dark themes.

✅ **User Location Tracking** - Allows users to find earthquakes near their location.

## 🚀 How It Works

1. **Fetch Data**: The app fetches earthquake data using the **USGS API**.
2. **Filter by Date**: Users can pick a date range to filter earthquake records.
3. **Display Earthquake Details**: Shows earthquake magnitude, time, location, and severity.
4. **Severity Indication**: Earthquakes above a certain magnitude appear in **Red**; others appear in **Green**.
5. **Dark/Light Mode**: Users can toggle between dark and light themes for a better experience.

## 🔮 Future Scope

🔹 **Push Notifications**: Alerts for nearby or significant earthquakes.

🔹 **Map Integration**: Visual representation of earthquakes on a world map.

🔹 **More Filtering Options**: Sorting based on intensity, location, etc.

🔹 **Offline Mode**: Save recent earthquake data for offline access.

Certainly! Below are the **Contributing Guidelines** and **Code of Conduct** sections formatted to match your README style. You can directly copy and paste them below your existing content.

---

## 🤝 Contributing Guidelines

We welcome contributions from everyone! To contribute:

- ✅ Always make your Pull Request (PR) to the `test1` branch, **not** to `master`.
- 📂 The `test1` branch is used for testing and review before merging stable features to `master`.
- 🔍 Your PR may be rejected or asked to be resubmitted if it's made to the wrong branch.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request describing your changes.

Please ensure your code follows the existing style and includes relevant tests or documentation if necessary.

---

## 🧾 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).
By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

---

## 📂 Installation & Setup

1. Clone the repository:  
   ```sh  
   git clone https://github.com/Fenirok/Earthquake_app.git  
   ```

2. Navigate to the project directory:  
   ```sh  
   cd Earthquake_app  
   ```

3. Install dependencies:  
   ```sh  
   flutter pub get  
   ```

4. Run the app:  
   ```sh  
   flutter run  
   ```

---

## 🤝 Contributing Guidelines

We welcome contributions from the community to improve the Earthquake Tracker App! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature/YourFeatureName
   ```
4. Make your changes and commit them:
   ```sh
   git commit -m 'Add some feature'
   ```
6. Push to your branch:
   ```sh
   git push origin feature/YourFeatureName
   ```
8. Open a Pull Request describing your changes.

Please make sure your code follows the existing style and is well-documented. Run all tests before submitting a PR.

---

## 📏 Code of Conduct

We are committed to providing a welcoming and inclusive environment for everyone. By participating in this project, you agree to follow our Code of Conduct:

* Be respectful and considerate.
* Avoid discriminatory or harassing behavior.
* Respect differing viewpoints and experiences.
* Use inclusive and constructive language.

Violations of the Code of Conduct may be reported by contacting the maintainers. Appropriate action will be taken to ensure a safe and respectful environment.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

Made with ❤️ using Flutter.
