# Modern Todo App

A beautiful, ultra-clean task management application with dark theme and smooth animations.

![Next.js](https://img.shields.io/badge/Next.js-15.0-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.6-blue)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4-38bdf8)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

### User Experience
- **Clean Dark Theme** - Easy on the eyes with sophisticated dark aesthetic
- **Smooth Animations** - Tasks slide in/out with beautiful transitions
- **Instant Feedback** - Real-time updates with every interaction
- **Persistent Storage** - Tasks saved automatically using localStorage
- **Responsive Design** - Perfect on desktop, tablet, and mobile

### Functionality
- ✅ Add, edit, and delete tasks
- ✅ Mark tasks as complete with animated checkbox
- ✅ Filter tasks (All / Active / Completed)
- ✅ Task counter showing active and completed items
- ✅ Clear all completed tasks at once
- ✅ Auto-save (survives page refresh)
- ✅ Empty state with elegant placeholder
- ✅ Smooth hover effects and transitions

### Design Details
- Premium card effects with subtle shadows
- Gradient purple/indigo accents
- Custom animated checkboxes
- Delete buttons appear on hover
- Smooth task completion animation
- Clean typography and spacing
- Professional color palette

## 🚀 Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** TailwindCSS
- **Animations:** Framer Motion
- **Storage:** Browser localStorage
- **Icons:** SVG (inline)

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/LyxdyHD/to-do-task.git

# Navigate to project
cd to-do-task

# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 🎨 Design Features

### Color Palette
- **Background:** Dark slate gradient (#0f172a to #1e293b)
- **Cards:** Translucent dark with backdrop blur
- **Accent:** Purple/Indigo gradient (#818cf8 to #6366f1)
- **Text:** Light slate tones for optimal readability

### Custom Components
- **Animated Checkboxes** - Rounded squares with smooth gradient fill
- **Premium Cards** - Glassmorphism effect with subtle borders
- **Hover Effects** - Smooth transitions on all interactive elements
- **Empty State** - Floating animation for visual interest

### Animations
- Slide-in effect for new tasks
- Smooth checkbox fill animation
- Fade-out on task deletion
- Hover states with scale transforms
- Filter button active state transitions

## 🛠️ Usage

### Adding Tasks
1. Type your task in the input field
2. Click "Add" or press Enter
3. Task appears with smooth animation

### Managing Tasks
- **Complete:** Click the checkbox
- **Delete:** Hover over task and click the × button
- **Filter:** Use All/Active/Completed buttons
- **Clear:** Click "Clear completed" to remove all done tasks

### Data Persistence
Tasks are automatically saved to browser localStorage. They persist across:
- Page refreshes
- Browser restarts
- Multiple sessions

## 📱 Responsive Design

Fully optimized for all screen sizes:
- **Desktop:** Spacious layout with hover effects
- **Tablet:** Adjusted spacing and touch-friendly buttons
- **Mobile:** Compact design with easy thumb reach

## 🎯 Use Cases

Perfect for:
- **Personal Task Management** - Daily to-do lists
- **Project Planning** - Break down tasks
- **Learning Projects** - Study Next.js and React patterns
- **Portfolio Showcase** - Demonstrate UI/UX skills
- **Code Reference** - Clean TypeScript and React examples

## 📂 Project Structure

```
to-do-task/
├── app/
│   ├── page.tsx          # Main todo component
│   ├── layout.tsx        # Root layout
│   └── globals.css       # Styles and animations
├── public/               # Static assets
├── package.json          # Dependencies
├── tailwind.config.ts    # Tailwind configuration
├── tsconfig.json         # TypeScript configuration
└── README.md             # Documentation
```

## 🔧 Customization

### Change Theme Colors
Edit `app/globals.css` to modify:
- Background gradients
- Accent colors
- Card styling

### Adjust Animations
Modify animation speeds in:
- Framer Motion props
- CSS keyframes
- Transition durations

### Add Features
Easy to extend with:
- Task priorities
- Due dates
- Categories/tags
- Search functionality
- Multiple lists

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

## 📝 License

MIT License - Free to use for personal and commercial projects.

## 💼 About

Created by [LyxdyHD](https://github.com/LyxdyHD)

Need a custom web application? Let's connect!

## 🌟 Show Your Support

If you like this project, give it a ⭐ on GitHub!

---

**Built with 💜 using Next.js, TypeScript, and TailwindCSS**