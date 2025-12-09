# AI Patrol System Tutorial for Unreal Engine

A comprehensive educational project teaching AI autonomous patrol navigation systems in Unreal Engine using Blueprint visual scripting.

---

## 📹 Video Tutorial

**[Watch the 13-minute Tutorial Video]**

Follow the Explain → Show → Try teaching model to learn AI navigation step-by-step.

---

## 📦 What's Included

### Complete Implementation
Fully functional AI patrol system demonstrating:
- Autonomous AI navigation using NavMesh
- Random patrol point generation
- Debug visualization (red spheres mark targets)
- Infinite loop behavior pattern

### Starter Template
Practice template with TODO markers for hands-on learning:
- Framework provided
- Core logic removed for student implementation
- Guided comments and hints included

### Documentation
- **Tutorial.pdf**: 10-page step-by-step guide with exercises
- **Pedagogical_Report.pdf**: 20+ page teaching analysis
- Implementation instructions
- Troubleshooting guide
- 5 practice exercises (basic to advanced)

---

## 🚀 Quick Start

### Prerequisites
- Unreal Engine 5.0 or later
- Basic Blueprint knowledge
- 2GB free disk space

### Installation

1. Clone this repository
```bash
git clone https://github.com/LinNEUdash/CYSE7270_TakeHomeFinal.git
cd AI_Move
```

2. Open the Complete project
```
Double-click AI_Move.uproject
```

3. Run the demo
```
Click Play button in editor
Press P to view Navigation Mesh (green areas)
Watch AI patrol autonomously
```

---

## 🎓 Learning Path

### For Beginners
1. Watch the video tutorial (13 minutes)
2. Read Tutorial.pdf sections 1-3
3. Open Complete project and examine blueprints
4. Try Starter project and complete TODOs
5. Complete exercises 1-3

### For Intermediate Learners
1. Review Complete implementation
2. Complete exercises 4-5
3. Extend with custom features
4. Integrate into your projects

---

## ✨ Key Features

- ✅ AI autonomously patrols within defined radius
- ✅ Random pathfinding on Navigation Mesh
- ✅ Visual debug feedback (sphere markers)
- ✅ Automatic obstacle avoidance
- ✅ Infinite loop behavior pattern
- ✅ Clean Blueprint implementation
- ✅ Fully commented and educational

---

## 📚 What You'll Learn

### Core Concepts
- Navigation Mesh (NavMesh) systems
- AI pathfinding with AI Move To
- Blueprint loop patterns
- Debug visualization techniques

### Practical Skills
- Configure Navigation System
- Implement autonomous AI behaviors
- Debug AI pathfinding issues
- Use Custom Events for loops
- Apply to game projects

---

## 🛠️ Technical Details

**Implementation:** Unreal Engine Blueprint
**AI System:** Navigation & Pathfinding
**Key Nodes:** Get Random Reachable Point, AI Move To
**Pattern:** Custom Event recursive loop
**Visualization:** Debug Sphere, NavMesh display

---

## 🎯 Practice Exercises

Included in Tutorial.pdf:

1. **Basic**: Modify patrol radius (change search distance)
2. **Basic**: Adjust movement speed (character movement settings)
3. **Basic**: Change wait time at targets (delay duration)
4. **Intermediate**: Implement fixed waypoint patrol
5. **Intermediate**: Add path visualization with debug lines

---

## 🐛 Troubleshooting

### AI Not Moving?
- Press P to verify NavMesh (green areas)
- Check NavMeshBoundsVolume covers area
- Verify AI Move To Pawn pin connected

### Sphere Position Wrong?
- Use variable to store target position
- Connect same variable to sphere and movement

### AI Walking Through Walls?
- Set wall Collision to BlockAll
- Rebuild navigation: Build → Build Paths

See Tutorial.pdf Chapter 6 for complete troubleshooting guide.

---

## 📖 Documentation

### Tutorial.pdf
- Introduction to AI patrol systems
- Technical theory (NavMesh, pathfinding)
- Step-by-step implementation guide
- 5 practice exercises with solutions
- Comprehensive debugging section

### Pedagogical_Report.pdf
- Teaching philosophy and methodology
- Technical deep dive
- Implementation analysis
- Assessment criteria
- Real-world applications

---

## 🔧 Project Structure

```
AI-Patrol-System/
├── Complete/                 # Full working implementation
│   └── AI_Patrol.uproject
├── Starter/                  # Practice template
│   └── AI_Patrol_Starter.uproject
├── Documentation/
│   ├── Tutorial.pdf          # 10-page guide
│   └── Pedagogical_Report.pdf # 20+ page report
├── Screenshots/              # Reference images
├── README.md                 # This file
└── LICENSE                   # MIT License
```

---

## 🎥 Video Contents

**Duration:** 12 minutes 53 seconds

**Segment 1: Explain (0:00-3:00)**
- AI patrol in games
- Navigation Mesh concepts
- Pathfinding principles

**Segment 2: Show (3:00-10:00)**
- Live implementation demo
- Blueprint walkthrough
- Parameter explanations

**Segment 3: Try (10:00-13:00)**
- Practice exercises
- Debugging tips
- Extension challenges

---

## 🌟 Extensions & Next Steps

### Beginner Extensions
- Multiple patrol zones
- Speed variations by area
- Day/night patterns

### Intermediate Extensions
- Behavior Tree integration
- State machines (patrol/chase/flee)
- Team coordination
- Animation synchronization

### Advanced Extensions
- Environment Query System (EQS)
- Machine learning integration
- Procedural route generation
- Multi-agent cooperation

---

## 📊 Performance

- **Single AI**: Negligible performance impact
- **10-20 AI**: Easily handled, no optimization needed
- **50+ AI**: Consider query frequency tuning
- **100+ AI**: Requires LOD and batch processing

See Pedagogical_Report.pdf Section 3.3 for detailed analysis.

---

## 🤝 Contributing

This is an educational project. Contributions welcome:
- Bug fixes
- Documentation improvements
- Additional exercises
- Translation to other languages

---

## 📜 License

MIT License - see LICENSE file for details.

Free to use for learning, teaching, and commercial projects.

---

## 👤 Author

**Yuxiao Lin**

Created for CYSE7270
Date: 2025/12/9

---

## 🙏 Acknowledgments

- Unreal Engine by Epic Games
- Recast Navigation library
- Game AI Pro community
- CYSE7270 teaching staff

---

## 📞 Support

For questions or issues:
- Review Tutorial.pdf troubleshooting section
- Check video tutorial timestamps
- Refer to Pedagogical_Report.pdf for detailed explanations

---

## 🔗 Additional Resources

- [Unreal Engine Documentation - Navigation System](https://docs.unrealengine.com/5.3/en-US/navigation-system-in-unreal-engine/)
- [AI Move To Node Reference](https://docs.unrealengine.com/5.3/en-US/BlueprintAPI/AI/Navigation/)
- [Blueprint Best Practices](https://docs.unrealengine.com/5.3/en-US/blueprint-best-practices-in-unreal-engine/)

---

**If this project helped you learn AI navigation, please ⭐ star the repository!**

---

© 2025 Yuxiao Lin - Educational Use