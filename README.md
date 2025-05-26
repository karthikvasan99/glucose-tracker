# Glucose Tracker App

An interactive, lightweight application for logging, visualizing, and analyzing blood glucose levels throughout the day using Gaussian Process regression.

This tool allows users to:
- Enter glucose measurements by clicking or editing
- Visually track blood glucose over a 24-hour period
- Fit a Gaussian Process curve to the data with adjustable parameters
- View and edit measurements in a synchronized day log table
- Export results (coming soon)

Built with:
- Python
- PyQt5
- pyqtgraph
- scikit-learn

---

## 🔬 Features

- **Interactive plot**: Add points by clicking on the graph
- **Gaussian Process smoothing**: Adjustable `length scale`, `alpha`, and `baseline`
- **Mean glucose calculation**: Displayed and updated live
- **Editable day log table**: Change or delete points directly
- **Bi-directional sync**: Edits in table or plot update each other
- **Cross-platform**: Works on Windows, macOS, and Ubuntu

---

## 🖥️ Screenshot

*(Add a screenshot of your app here if you like)*

---

## 🚀 Getting Started

See [`INSTALL.md`](INSTALL.md) for detailed setup instructions on macOS and Ubuntu.

---

## 🧪 Usage

To launch the app:

```bash
python main.py
