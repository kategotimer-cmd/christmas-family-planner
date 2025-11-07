# 🎄 Christmas in Austin - Family Planner

A beautiful, interactive web application for planning the Gotimer family Christmas celebration in Austin, Texas (December 23-29, 2025).

![Christmas Planner](https://img.shields.io/badge/Christmas-2025-green)
![Status](https://img.shields.io/badge/status-active-success)

## ✨ Features

### 📅 **Calendar Management**
- 7-day calendar view (Dec 23-29, 2025)
- Color-coded events (Flights, Meals, Activities)
- Chronological sorting by time
- Multi-person attendee tracking with "Select All" option
- Add, edit, and delete events with ease

### 🎁 **Wish Lists**
- Individual wish lists for 11 family members
- Add gift ideas with title, link, and details
- Edit and remove gift suggestions
- Grouped view showing all wish lists at once
- Clothing size tracking (shirt, pants, shoes)

### 🏠 **Accommodations**
- Manage sleeping arrangements across 6 nights
- Two locations: Chateau Gotimer and McColl-Stanton Manor
- Support for multiple family groups per location
- Summary view and detailed nightly assignments
- Checkbox-based group assignments

### 🌟 **Live Widgets**
- **Countdown Timer**: Live countdown to Christmas Day
- **Weather Widget**: Real-time Austin, TX weather (via wttr.in API)
- **Holiday Trivia**: Rotating fun Christmas facts every 10 seconds

### 💾 **Data Persistence**
- All data automatically saved to browser localStorage
- No backend required - works entirely offline
- Automatic migration of data format updates

## 🚀 Quick Start

### Option 1: Open Directly
Simply open `christmas-family-planner.html` in any modern web browser.

### Option 2: Run Local Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then visit: `http://localhost:8000/christmas-family-planner.html`

## 🎨 Design

- **Color Scheme**: Shades of green (forest green, sage, olive)
- **Typography**: 
  - Title: Elegant cursive font (Lucida Handwriting)
  - Body: Modern Inter font
- **Responsive**: Works on desktop, tablet, and mobile devices
- **Theme**: Festive with animated snowflakes

## 👥 Family Members

The planner supports 11 family members:
- Kate & Charlie
- Greg, Lily
- Becky, Evan & Liam
- Bill & Stacy
- Gail & Bob

## 📱 Browser Compatibility

Works in all modern browsers:
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks required
- **Single File Application** - Everything in one HTML file
- **LocalStorage API** - For data persistence
- **Fetch API** - For weather data
- **Google Fonts** - Inter font family

## 📊 Data Storage

All data is stored in browser localStorage under these keys:
- `gotimer-events` - Calendar events
- `gotimer-wishlists` - Gift ideas for each person
- `gotimer-accommodations` - Nightly sleeping arrangements
- `gotimer-clothing-sizes` - Clothing size information

## 🌐 API Used

- **Weather**: [wttr.in](https://wttr.in/) - Free weather API, no API key required
- **Fonts**: [Google Fonts](https://fonts.google.com/) - Inter font family

## 🎯 Use Cases

- **Event Planning**: Coordinate flights, meals, and activities
- **Gift Shopping**: Track gift ideas and clothing sizes
- **Accommodation Management**: Organize who stays where each night
- **Family Coordination**: Keep everyone informed with shared access

## 📝 License

This project is open source and available for personal use.

## 🎅 Happy Holidays!

Made with ❤️ for the Gotimer family Christmas 2025 in Austin, TX

---

**Note**: This is a client-side only application. All data is stored locally in your browser. To share data across devices, you'll need to manually export/import or deploy with a backend storage solution.
