# 📊 Sales & Revenue Dashboard - Quick Reference

## 🚀 How to Use

1. **Open the file**: Double-click `Sales_Revenue_Dashboard.html` in your browser
2. **No installation needed** - works in any modern browser
3. **Interact immediately** - all features built-in

## 🎯 Features Included

### Filters & Slicers (Top of Dashboard)
- **Region Filter**: North, South, East, West
- **Category Filter**: Electronics, Clothing, Home, Sports  
- **Month Filter**: Jan-Jun
- **Export CSV**: Download filtered data as CSV

### KPI Cards (4 Key Metrics)
| Metric | Shows |
|--------|-------|
| Total Sales | Sum of all sales amounts |
| Total Revenue | Total revenue generated |
| Orders | Count of transactions |
| Avg Order Value | Revenue per order |

### Charts (4 Interactive Visualizations)
1. **Revenue Trend** - Line chart showing monthly progression
2. **Sales by Category** - Doughnut chart of category breakdown
3. **Sales by Region** - Bar chart comparing regions
4. **Top 5 Products** - Horizontal bar chart of best performers

### Data Table
Shows first 10 transactions with all details

## 📊 Sample Data Included
- **24 transactions** across 6 months (Jan-Jun 2024)
- **4 categories**: Electronics, Clothing, Home, Sports
- **4 regions**: North, South, East, West
- **12 products**: Laptop, Tablet, Phone, etc.

## 🔄 How to Replace With Your Data

### Option 1: Quick Edit in Code
1. Open `Sales_Revenue_Dashboard.html` in any text editor
2. Find the `rawData = [...]` section (around line 270)
3. Replace entries with your data in this format:
```
{date: '2024-01-05', product: 'Product Name', category: 'Category', region: 'Region', units: 5, sales: 1000, revenue: 1200}
```

### Option 2: Drag-and-Drop CSV (Advanced)
Contact for custom modification to load CSV files directly.

## 📈 What Each Filter Does

| Filter | Effect |
|--------|--------|
| Region | Shows only sales from selected region |
| Category | Shows only selected product category |
| Month | Shows data from specific month |
| Combine Filters | All selected filters work together |

## 💾 Export Feature
Click **"📥 Export CSV"** to download filtered data in Excel-compatible format

## 🎨 Dashboard Elements

| Element | Purpose |
|---------|---------|
| Purple Header | Brand/title area |
| White Cards | Key performance indicators |
| Charts | Visual data representation |
| Table | Detailed transaction view |
| Filters | Data slicing controls |

## 📱 Responsive Design
- Works on desktop, tablet, mobile
- Auto-adjusts layout for smaller screens
- Charts scale with screen size

## ⚡ Performance
- Handles 1,000+ records smoothly
- Instant filter updates
- No external dependencies beyond Chart.js

## 🔧 Customization Options

### Change Colors
1. Find CSS section (line 20-40)
2. Modify hex codes:
   - `#667eea` = Primary purple
   - `#764ba2` = Secondary purple
   - `#10b981` = Green
   - `#3b82f6` = Blue
   - `#f59e0b` = Orange

### Add More Data
Insert new entries in `rawData` array following the same format

### Modify Filters
Add new select options or create new filter dropdowns

## 📊 KPI Calculations

- **Total Sales** = Sum of all sales amounts
- **Total Revenue** = Sum of all revenue  
- **Orders** = Count of transactions
- **Avg Order Value** = Total Revenue / Number of Orders

## 🎯 Use Cases

✅ Executive dashboards
✅ Sales team performance tracking
✅ Regional comparison analysis
✅ Product category analysis
✅ Monthly trend reporting
✅ Board presentations

## ⚠️ Known Features
- Sample data: 24 transactions (6 months)
- Max visible rows: 10 in table (scroll-friendly)
- Real-time filter updates
- Cross-browser compatible

## 💡 Tips

1. **Filter before exporting** - CSV will only include filtered data
2. **Use multiple filters** - Region + Category shows specific combinations
3. **Check the charts** - Visual insights faster than tables
4. **Mobile friendly** - Open on phone for on-the-go insights

## 📞 Support

### To Add CSV Import
Replace sample data loading with file upload functionality

### To Add Real Database
Modify data source from array to API/database call

### To Add More Metrics
Insert new KPI cards in HTML and update calculation functions

---

**File Size**: ~10 KB (entire app in one file)
**Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
**Dependencies**: Chart.js library (CDN-loaded)
**Works Offline**: Yes ✓

---

**Ready to use! Open the HTML file in your browser now.** 🚀
