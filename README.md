# 🧒 Childcare Cost Calculator

A free, interactive calculator to help families estimate their total annual childcare costs — including school tuition, extended programs, summer care, and backup care for school closure days.

**[➡️ Try the Calculator](https:///atif-adam.github.io/childcare-calculator/)** *(update this link after deploying)*

---

## ✨ Features

- **Fully customizable** — Enter your own school's rates and programs
- **12-month view** — See costs across the full year, not just school months
- **Backup care calculator** — Factor in nanny/babysitter costs for school closures
- **Summer program support** — Toggle on/off and configure which months
- **Interactive charts** — Visualize monthly costs, cumulative spend, and cost composition
- **Print/PDF export** — Save or print your personalized cost breakdown
- **No account required** — Runs entirely in your browser, no data stored

---

## 🏫 Eliot-Pearson Children's School Preset

Families at **Eliot-Pearson Children's School** (Tufts University) can load pre-configured rates with one click:

1. Select your child's room from the dropdown:
   - 🌈 Rainbow Room (ages 2y 9m – 3y)
   - 💜 Purple Room (ages 3 – 4)
   - 💚 Green Room (ages 4 – 5)  
   - 🧡 Orange Room (ages 5 – 6)

2. Click **"Load Rates & Calendar"**

3. All 2026-2027 tuition rates and 2025-2026 school closure days load automatically!

> **Note:** Orange Room has a different rate structure since the base program runs until 3pm (vs 12:30pm for other rooms).

---

## 📖 How to Use

### For Any School

1. **School & Rates tab** — Enter your school name and all tuition rates
2. **Programs tab** — Select how many days/week for Extended Day and Late Afternoon programs
3. **Summer Program tab** — Toggle on if your school offers summer, select months
4. **Backup Care tab** — Enter your nanny/sitter hourly rate and closure days per month
5. **Review** — See your total annual cost and monthly breakdown
6. **Print/Save** — Click the green button to export as PDF

### Finding Your School's Closure Days

Check your school's annual calendar and count weekdays for:
- Staff development days
- Holiday breaks (Thanksgiving, Winter, Spring)
- Conference days
- Summer closure (if no summer program)

---

## 💡 Tips

- **Don't forget summer!** — July and August can add $5,000-10,000+ in nanny costs if your school doesn't offer a summer program
- **Dependent Care FSA** — You can save ~$1,500-2,000 in taxes by contributing to a Dependent Care FSA ($5,000 limit)
- **Compare scenarios** — Try different program day combinations to find the best value
- **Check marginal costs** — Sometimes adding more program days is cheaper than equivalent nanny hours

---

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** — No frameworks, no build step
- **Chart.js** — For interactive visualizations
- **Runs locally** — Can be opened directly in any browser
- **Privacy-first** — No data is sent anywhere; everything stays in your browser

---

## 📝 Contributing

Found a bug or want to add your school as a preset? 

1. Fork this repository
2. Make your changes
3. Submit a pull request

To add a new school preset, edit the `loadEPCS()` function pattern in the HTML file.

---

## 📄 License

MIT License — Free to use, modify, and share.

---

## 🙏 Acknowledgments

Built by a parent, for parents. Because childcare costs are complicated enough without needing a spreadsheet degree.

---

*Questions or suggestions? Open an issue!*
