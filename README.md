# Family Events Dashboard

A beautiful, easy-to-use dashboard for tracking family events, activities, and signup deadlines in Jackson, Wyoming.

![Family Events Dashboard](https://img.shields.io/badge/status-live-success)
![No Build Required](https://img.shields.io/badge/build-none-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 📅 **Visual Calendar** - See all your family events at a glance
- 🔔 **Deadline Tracking** - Never miss a signup deadline again
- 🎿 **Priority Events** - Ski pass reminders, season passes, and important dates
- 🏫 **School Breaks** - Auto-reminders for holiday care and camps
- 👶 **Per-Child Filtering** - View events by kid (Ruby & Duncan)
- ♿ **Adaptive Program Support** - Flag and filter inclusive programming
- 🔗 **Direct Signup Links** - One-click access to registration pages
- 🎨 **Beautiful Design** - Custom Jackson-themed mountain illustration

## 🚀 Quick Start

### View Live Demo
👉 **[Your Vercel URL here]** 👈

### Run Locally
Simply download `index.html` and double-click it. No installation needed!

## 📱 Use Cases

Perfect for busy families who need to:
- Track dance recitals, soccer tryouts, and swim lessons
- Remember school holiday care signup deadlines
- Coordinate adaptive programming for kids with special needs
- Get early bird pricing on ski passes and lessons
- Share a family calendar between parents

## 🎯 How It Works

1. **View Events** - See all upcoming activities in one place
2. **Filter by Kid** - Click Ruby or Duncan to see their specific events
3. **Add New Events** - Click "+ Add Event" to create custom entries
4. **Never Miss Deadlines** - Urgent deadlines are highlighted in red
5. **Click to Sign Up** - Every event links directly to the registration page

## 🛠️ Customization

Want to customize for your own family?

1. Open `index.html` in any text editor
2. Find the `CHILDREN` array (around line 450)
3. Update names and ages:
   ```javascript
   const CHILDREN = [
     { id: "all", label: "All Kids" },
     { id: "yourchild1", label: "Your Child (Age)" },
     { id: "yourchild2", label: "Your Child (Age)" },
   ];
   ```
4. Update the `INITIAL_EVENTS` array with your events
5. Save and refresh!

## 📍 Jackson, Wyoming Events Included

Pre-loaded with local resources:
- Jackson Rec Center programs
- Jackson Hole Mountain Resort (ski passes & lessons)
- Expanded Learning Collective
- Teton Village activities
- Local adaptive programming

## 🔄 Updating

### On GitHub:
1. Click `index.html`
2. Click the ✏️ (pencil) icon
3. Make your changes
4. Commit changes

Vercel will automatically redeploy in ~30 seconds!

### In the Browser:
- Events added through the dashboard are saved locally in your browser
- They won't sync between devices (yet!)
- For permanent changes, edit the HTML file

## 🌐 Deployment

This project is designed to deploy anywhere:

- **Vercel** (recommended) - Free, automatic deploys from GitHub
- **Netlify** - Also free with GitHub integration
- **GitHub Pages** - Free static hosting
- **Any web host** - Just upload the single HTML file

See [HTML_DEPLOY_INSTRUCTIONS.md](HTML_DEPLOY_INSTRUCTIONS.md) for detailed steps.

## 🔮 Future Enhancements

Want to take it further? Consider adding:

- 📧 **Email notifications** - Weekly digest of upcoming events
- 📱 **Mobile app** - Convert to React Native for push notifications
- 🔐 **User accounts** - Multiple families with private dashboards
- 🗓️ **Calendar sync** - Export to Google Calendar or Apple Calendar
- 🤖 **AI event discovery** - Auto-find local events based on your interests

See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) for implementation guides.

## 🤝 Contributing

This dashboard was built for one family but designed to help many. Feel free to:

- Fork this repo for your own family
- Customize the events and kids
- Share with other Jackson families
- Submit improvements via pull requests

## 📄 License

MIT License - feel free to use and modify for your family!

## 💡 Tips for Use

- **Bookmark it** - Add to your phone home screen for quick access
- **Share the URL** - Send to your partner, grandparents, babysitters
- **Update weekly** - Check for new local events every Sunday
- **Set reminders** - The dashboard shows you what's urgent, but you still need to take action!

## 🆘 Need Help?

- **Build errors?** This is just HTML - there's nothing to build!
- **Not working?** Make sure you renamed it to `index.html` on GitHub
- **Want to customize?** Open the file in VS Code or any text editor
- **Questions?** Open an issue on GitHub

---

Built with ❤️ for families in Jackson, Wyoming 🏔️

**Ruby (4)** - Dance, Soccer, Ski Lessons  
**Duncan (3)** - Adaptive Programs, Swimming, Dance
