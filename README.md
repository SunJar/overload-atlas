# 🗺️ Overload Atlas

**Sensory Experience Simulator for Neurodivergent Students**

[![Made with Claude](https://img.shields.io/badge/Made%20with-Claude%20AI-blue)](https://claude.ai)
[![Three.js](https://img.shields.io/badge/Three.js-r128-black)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Experience campus environments through a neurodivergent lens. Navigate, learn, and prepare with AI-powered sensory guidance.

![Overload Atlas Demo](https://via.placeholder.com/800x400/028090/FFFFFF?text=Overload+Atlas+-+Demo+Screenshot)

## 🎯 The Problem

**1 in 5** college students experience sensory processing challenges, yet **zero tools exist** to help them preview and prepare for campus sensory conditions.

Students with autism, ADHD, PTSD, migraines, or sensory sensitivities face daily uncertainty:
- Will the cafeteria be overwhelming today?
- Is there a quiet study spot in the library?
- Which route to class has the least sensory load?

**73%** of neurodivergent students report anxiety from unpredictable sensory environments.

## 💡 My Solution

**Overload Atlas** is an immersive 3D sensory simulation that lets students experience and understand NJIT campus environments *before* visiting them in real life.

### Key Features

- 🎮 **First-Person Navigation** - Explore 4 campus locations with WASD controls
- 🤖 **Real-Time Claude AI Guidance** - Get zone-specific coping strategies and survival tips
- 📊 **Live Sensory Metrics** - Track noise, light, and crowd levels in real-time
- 🗺️ **Mini-Map & Navigation** - Spatial awareness with live player position
- ⚡ **Stress Meter** - Visual feedback on cumulative sensory load
- 🎯 **Zone-Specific Advice** - Tailored recommendations for each area

## 🏛️ Simulated Locations

1. **Quiet Library Study Room** - Low sensory sanctuary (1/5 noise, 2/5 light, 1/5 crowd)
2. **Campus Center Cafeteria** - High intensity chaos (5/5 noise, 4/5 light, 5/5 crowd)
3. **Standard Lecture Hall** - Moderate balanced environment (3/5/3)
4. **Busy ECEC Hallway** - Challenging corridor with fluorescent flicker (4/5 noise, 5/5 light)

Each location has **3 distinct zones** with unique sensory profiles and AI-generated guidance.

## 🤖 Claude AI Integration

Overload Atlas uses **Claude Sonnet 4.5** to provide three types of real-time guidance:

1. **📋 Analysis** - Current environment assessment and who it's suitable for
2. **💡 Quick Insights** - Research-backed statistics and facts
3. **🛡️ Survival Strategies** - Concrete coping mechanisms and exit plans

Example from Cafeteria - Main Dining Hall:
> **Analysis:** Peak chaos: 200+ simultaneous conversations, chair scraping, overlapping music. Studies show this environment triggers fight-or-flight in 60% of autistic individuals.
>
> **Insight:** Acoustic echo chamber effect amplifies all sounds. Hard surfaces reflect noise instead of absorbing it.
>
> **Strategy:** Strongly recommend: noise-canceling headphones + tinted glasses. Eat quickly and leave. 15-minute max exposure recommended.

## 🛠️ Tech Stack

**Frontend**
- Three.js r128 - 3D rendering engine
- HTML5 Canvas - Mini-map visualization
- Vanilla JavaScript - Zero dependencies for core logic

**AI/ML**
- Claude Sonnet 4.5 API - Natural language processing
- Contextual advice generation
- Real-time sensory analysis

**Features**
- Custom first-person controls with pointer lock
- AABB collision detection
- Quaternion-based camera rotation
- Dynamic HUD with multiple info panels
- Stress calculation algorithm

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/SunJar/overload-atlas.git
cd overload-atlas

# Open in browser
open index.html
```

No build process needed! Just open `index.html` in any modern browser.

### Controls

- **W/A/S/D** - Move forward/left/backward/right
- **Mouse** - Look around (click to lock cursor)
- **Space** - Jump to next room
- **ESC** - Exit pointer lock

### Settings

- **Sensitivity slider** - Adjust mouse look speed
- **Invert Y-axis** - Toggle vertical look direction

## 📊 Impact

### Immediate Benefits

✅ Reduce pre-visit anxiety for sensory-sensitive students  
✅ Enable informed navigation decisions  
✅ Provide practical accessibility tool for neurodivergent community  
✅ Demonstrate AI's potential in disability support

### Research-Backed Design

Our sensory ratings and advice are informed by:
- Studies on cortisol reduction in quiet spaces (25% decrease)
- Decibel measurements of common campus environments
- Fluorescent flicker rates and migraine triggers (60Hz, affects 30% of population)
- Autism research on sensory overload and fight-or-flight responses

## 🔮 Future Roadmap

- [ ] Expand to all NJIT campus buildings
- [ ] User-submitted sensory reports (crowdsourcing)
- [ ] Mobile app for on-the-go access
- [ ] Integration with campus maps and schedules
- [ ] Partnership with NJIT Disability Services
- [ ] VR headset support for full immersion
- [ ] Time-of-day simulation (morning vs. afternoon crowds)
- [ ] Weather impact on sensory conditions

## 🏆 Built At

**NJIT Claude Builder Club Spring 2026 Hackathon**  
April 26, 2026 | Built in <10 hours

**Theme:** Social Impact - AI for Human Flourishing  
**Track:** Health & Wellbeing

## 👥 Developer

Sanzhar Sharipov - Developer & Designer (worked solo)

## 🙏 Acknowledgments

- **Anthropic** - For Claude AI and the Builder Club program
- **NJIT Disability Services** - For inspiration and real-world context
- **Neurodivergent students** - This is for you

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details

## 🔗 Links

- **Live Demo:** [GitHub Pages](https://[your-username].github.io/overload-atlas)
- **Devpost:** [Project Submission](https://devpost.com/software/overload-atlas)
- **Video Demo:** [YouTube](https://youtube.com/...)

---

*Empowering neurodivergent students to navigate campus with confidence.*
