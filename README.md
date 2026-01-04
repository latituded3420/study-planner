# Personalized Study Planner

A comprehensive full-stack web application designed to help students prepare efficiently for exams with automated study scheduling, subject tracking, Pomodoro timer, and real-time progress monitoring.

## 🎯 Features

### Core Features
- **Subject Management**: Add subjects with exam dates, priority levels, and study hour requirements
- **Smart Study Plan Generation**: Intelligent algorithm allocates study hours based on urgency and priority
- **Pomodoro Timer**: Customizable focus sessions (default 25 mins) with break periods (default 5 mins)
- **Progress Tracking**: Real-time monitoring of overall progress, daily progress, and exam countdowns
- **Upcoming Exams**: Visual list of exams sorted by urgency (next 7 days)
- **Dark/Light Theme**: Toggle between themes for comfortable studying at any time
- **Study Sessions**: Record and track completed study sessions for each subject
- **Browser Notifications**: Desktop notifications for timer alerts and session completions
- **Export/Import**: Save and load study plans in JSON format

## 💻 Tech Stack

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling with animations
- **Bootstrap 5** - Responsive design framework
- **JavaScript (ES6+)** - Client-side logic and interactivity
- **FontAwesome 6.4** - Icon library
- **Day.js** - Date manipulation
- **Howler.js** - Audio alerts for timer

### Backend
- **Node.js + Express.js** - API server (optional, for advanced features)
- **REST API** - Client-server communication
- **JSON** - Data storage and exchange

### Features Implemented
- Client-side data storage (localStorage)
- Responsive design (mobile, tablet, desktop)
- Real-time progress calculations
- Dark mode support

## 📁 Project Structure

```
study-planner/
├── index.html          # Main HTML file
├── styles/
│   └── style.css       # Custom CSS styling
├── js/
│   ├── app.js          # Main application controller
│   ├── timer.js        # Pomodoro timer implementation
│   ├── studyPlanner.js # Study plan algorithm and statistics
│   └── inti.js         # Global initialization
├── README.md           # This file
└── [Optional Backend]
    ├── server.js       # Express server
    ├── api/
    └── database/
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required for basic functionality
- Optional: Node.js for backend API

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/latituded3420/study-planner.git
   cd study-planner
   ```

2. Open in browser:
   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   python -m http.server 8000
   # Then visit: http://localhost:8000
   ```

3. Start studying:
   - Add subjects with exam dates
   - Set your daily study hours available
   - Generate a personalized study plan
   - Start the timer and begin your focused study sessions

## 📖 How to Use

### 1. Add Subjects
- Enter subject name
- Select exam date
- Choose priority level (High, Medium, Low)
- Set total study hours needed
- Click "Add Subject"

### 2. Configure Study Settings
- Set daily study hours available
- Select study start date
- Click "Generate Study Plan"

### 3. Use the Timer
- Adjust session duration (default: 25 mins)
- Adjust break duration (default: 5 mins)
- Click "Start" to begin
- Timer automatically switches between study and break
- Enable/disable sound alerts

### 4. Track Progress
- View overall progress percentage
- See today's progress
- Check upcoming exams (next 7 days)
- Monitor study sessions for each subject

## 🧠 Study Plan Algorithm

The smart allocation algorithm considers:
1. **Urgency Weight** - Days until exam (higher = more urgent)
2. **Priority Weight** - Subject importance (High: 1.5x, Medium: 1.0x, Low: 0.7x)
3. **Remaining Hours** - Hours still needed for each subject

Formula: `Allocated Hours = (Subject Weight / Total Weight) × Daily Hours`

## 📊 What I Learned

- Full-stack web application development
- Responsive design and mobile optimization
- JavaScript ES6+ features (classes, async/await, event listeners)
- Algorithm design for smart scheduling
- DOM manipulation and real-time UI updates
- Time management with Pomodoro technique
- Data persistence with localStorage
- Browser APIs (Notification, Audio Context, Fetch)
- Bootstrap framework for rapid development
- Project planning and structure

## 🔧 Future Enhancements

- Backend API integration for multi-device sync
- Database storage (MongoDB/PostgreSQL)
- User authentication and profiles
- Cloud sync across devices
- Advanced analytics and insights
- Collaborative study plans
- Mobile app version (React Native)
- Integration with calendar apps
- AI-powered study recommendations
- Study group features

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📝 Notes

- All data is stored locally in your browser (localStorage)
- No data is sent to external servers (unless you set up the backend)
- Study plans can be exported and imported as JSON files
- Sound alerts require user gesture (click/interact first)
- Browser notifications require permission

## 🎓 Use Cases

- **College Students** - Prepare for final exams
- **Competitive Exams** - JEE, NEET, GMAT, GRE, etc.
- **Certification Prep** - AWS, Google, Microsoft certifications
- **Language Learning** - Track multiple language subjects
- **Skill Development** - Organize learning modules

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Salim (BCA Student)**
- GitHub: [@latituded3420](https://github.com/latituded3420)
- Focus: Web development and software engineering
- Based in: Pune, Maharashtra, India

## ⭐ Support

If you found this helpful, please star the repository!

---

**Last Updated**: January 2026
**Version**: 1.0.0
