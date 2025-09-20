# Swarna Khata Book - Live Rate 📱

A modern Android application that provides real-time gold and silver prices with live updates, designed for jewelry businesses and precious metal traders.

## 🌟 Features

### Real-Time Price Tracking
- **Live Gold Prices** - Real-time gold rates per 10 grams in Indian Rupees
- **Live Silver Prices** - Real-time silver rates per kilogram in Indian Rupees
- **Auto-Refresh** - Prices update automatically every 60 seconds
- **Price Change Indicators** - Visual trend indicators showing price increases/decreases
- **Percentage Change** - Detailed change information with both absolute and percentage values

### User Interface
- **Modern Material Design** - Clean and intuitive interface
- **Real-Time Animations** - Smooth price change animations with color-coded indicators
- **Connection Status** - Live internet connectivity indicator
- **Navigation Drawer** - Easy access to app features and external links

### Technical Features
- **Smart Caching** - Efficient API usage with intelligent caching mechanisms
- **Offline Handling** - Graceful handling of network connectivity issues
- **Currency Conversion** - Automatic USD to INR conversion using live exchange rates
- **Firebase Integration** - Real-time exchange rate updates via Firestore

## 🛠️ Technical Stack

### Core Technologies
- **Language**: Kotlin
- **Platform**: Android (API 26+)
- **Architecture**: MVVM with Repository Pattern
- **UI Framework**: Android Views with ViewBinding

### Libraries & Dependencies
- **Networking**: Retrofit 2 with Moshi for JSON parsing
- **Database**: Firebase Firestore for exchange rate storage
- **UI Components**: Material Design Components
- **Navigation**: Android Navigation Component
- **HTTP Client**: OkHttp with logging interceptor

### API Integration
- **Gold API**: Real-time precious metal prices
- **Firebase Firestore**: Live USD to INR exchange rates
- **Currency Conversion**: Automatic price conversion from USD to INR

## 📱 App Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/9dee94c0-2e2b-417d-a59d-529830bd265e" width="200"/>  
  <img src="https://github.com/user-attachments/assets/30f5697b-e844-41de-8a5b-1702cea69a71" width="200"/>
</p>

## 🚀 Key Functionalities

### Live Price Display
- Displays current gold price per 10 grams
- Shows current silver price per kilogram
- Real-time price updates with visual feedback
- Color-coded trend indicators (green for increase, red for decrease)

### Price Change Tracking
- Absolute price change in Indian Rupees
- Percentage change calculation
- Visual trend arrows (up/down)
- Smooth animations for price changes

### Smart Data Management
- API call optimization with 60-second intervals
- Cached data usage to reduce API calls
- Automatic retry mechanisms for failed requests
- Graceful error handling and user feedback

### User Experience
- Intuitive navigation with drawer menu
- Share app functionality
- Rate app integration with Play Store
- Contact support via WhatsApp
- Cross-app integration with main Swarna Khata Book app

## 🔧 Technical Implementation

### Architecture
- **MVVM Pattern**: Clean separation of concerns
- **Repository Pattern**: Centralized data management
- **Service Layer**: Dedicated services for API calls and data processing
- **Utility Classes**: Reusable conversion and formatting utilities

### Data Flow
1. **API Integration**: Fetches gold/silver prices from external API
2. **Exchange Rate**: Retrieves USD to INR rate from Firebase Firestore
3. **Currency Conversion**: Converts USD prices to INR using live exchange rates
4. **UI Updates**: Displays converted prices with trend indicators
5. **Caching**: Stores prices for offline usage and API optimization

### Performance Optimizations
- Smart caching to minimize API calls
- Background processing for data updates
- Efficient memory management
- Optimized UI rendering with ViewBinding

## 📊 Project Structure

```
app/
├── src/main/java/com/scr/swarnakhatabookliverate/
│   ├── fragments/           # UI fragments
│   ├── models/             # Data models and DTOs
│   ├── network/            # API service and Retrofit client
│   ├── services/           # Firebase and data services
│   ├── utils/              # Utility classes and helpers
│   └── MainActivity.kt     # Main activity
├── src/main/res/           # Resources (layouts, drawables, values)
└── build.gradle.kts        # Build configuration
```

## 🎯 Target Audience

- **Jewelry Business Owners** - Track precious metal prices for business decisions
- **Precious Metal Traders** - Monitor real-time market rates
- **Gold/Silver Investors** - Stay updated with current market prices
- **Jewelry App Users** - Complement to the main Swarna Khata Book application

## 🔗 Related Apps

This app is designed to work alongside the main **Swarna Khata Book** application, providing live price data for jewelry business management.

## 📱 Requirements

- **Android Version**: 8.0 (API 26) or higher
- **Internet Connection**: Required for live price updates
- **Storage**: Minimal storage requirements

## 🚀 Getting Started

*Note: This is a showcase project. The app is available on Google Play Store for download.*

## 📞 Support

For support and inquiries:
- **WhatsApp**: +91 9928015991
- **Email**: Contact through the app's support section

## 📄 License

This project is for showcase purposes. All rights reserved.

---

**Swarna Khata Book - Live Rate** - Your trusted companion for real-time precious metal prices! ✨
