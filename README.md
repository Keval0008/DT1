# BSRS Tool v2.0

A minimal, clean desktop application for processing BSRS (Business Support Role System) Excel files with a focus on simplicity and ease of use.

## ✨ Minimal Design Features

### Clean Interface
- **Simplified UI**: Minimal, distraction-free design
- **Clean Typography**: Modern Segoe UI fonts throughout
- **Calm Colors**: Soft, professional color palette
- **Focused Layout**: Essential functions only, no clutter

### User-Friendly Experience
- **Simple File Selection**: Easy drag-and-drop style file choosers
- **Clear Process Flow**: Logical step-by-step workflow  
- **Minimal Text**: Concise instructions and messaging
- **Modern Buttons**: Clean, borderless button design
- **Progress Tracking**: Subtle progress indicators

## 🎯 Core Functions

### Process Files
1. **Select Files**: Choose one or more BSRS Excel files
2. **Choose Destination**: Pick where to save processed files
3. **Process**: Click the process button and wait for completion

### Admin Consolidation (Admin Users Only)
1. **Select Input Folder**: Choose folder with multiple BSRS files
2. **Select Output Folder**: Pick destination for consolidated file
3. **Consolidate**: Merge all files into organized output

## 🚀 Quick Start

### Installation
```bash
pip install -r requirements.txt
```

### Run Application
```bash
python main_app.py
```

## 💡 Key Improvements

### From Complex to Simple
- **Removed**: Tabs, complex panels, verbose instructions
- **Added**: Clean layouts, minimal dialogs, intuitive flow
- **Focused**: Essential features only, reduced cognitive load

### Modern UI Elements
- **Flat Design**: No borders or 3D effects
- **Clean Typography**: Consistent font hierarchy
- **Subtle Colors**: Professional blue/gray palette  
- **Smooth Interactions**: Hover effects and visual feedback

## ⚙️ Configuration

Edit `config.py` for customization:

```python
# Add your username to admin list for consolidation features
ADMIN_USERS = ["admin1", "admin2", "your_username"]

# Adjust visual settings
WINDOW_SIZE = "600x450"  # Compact window size
COLORS = {
    'primary': '#2563eb',      # Clean blue
    'success': '#10b981',      # Clean green
    'error': '#ef4444',        # Clean red
    'background': '#ffffff'    # Pure white
}
```

## 📁 Project Structure

```
bsrs-tool/
├── main_app.py           # 🚀 Main minimal application
├── config.py             # ⚙️ Clean configuration 
├── utils.py              # 🔧 Simple utilities
├── validation.py         # ✅ Smart validation
├── business_logic.py     # 💼 Core processing
├── ui_components.py      # 🎨 Minimal UI widgets
├── requirements.txt      # 📦 Dependencies
├── README.md            # 📖 This guide
└── app_v2.py            # 📜 Original version (reference)
```

## 🎨 Design Principles

### Minimalism
- **Less is More**: Only essential UI elements
- **Clean Lines**: Simplified layouts without clutter
- **Purposeful Space**: Generous white space for breathing room

### Clarity
- **Clear Hierarchy**: Obvious information structure
- **Readable Text**: Appropriate font sizes and weights
- **Intuitive Flow**: Logical progression through tasks

### Modern Feel
- **Flat Design**: Contemporary visual style
- **Subtle Shadows**: Minimal depth for card-like elements
- **Clean Typography**: Modern, readable fonts

## 🛠️ Usage Guide

### Basic Workflow
1. **Launch**: Run `python main_app.py`
2. **Select**: Choose your BSRS Excel files
3. **Destination**: Pick where to save results
4. **Process**: Click the blue Process Files button
5. **Done**: Files are processed with validation

### Validation Handling
When issues are found, you get simple options:
- **Save Anyway**: Continue with highlighted errors
- **Save for Review**: Create detailed error report
- **Cancel**: Stop and fix issues first

### Admin Features
Admin users see an additional **Consolidate** tab for merging multiple files into organized sheets.

## 📋 File Requirements

### Input Files
- **Format**: Excel (.xlsx) files only
- **Structure**: Standard BSRS template with:
  - 'Sheet1' with 3-level headers
  - 'L&D' sheet with user information
  - Role holder columns (PS ID and Name)

### Output Files
- **Formatted**: Professional Excel styling
- **Timestamped**: Automatic naming with date/time
- **Validated**: Error highlighting and logging
- **Enriched**: Additional user data populated

## 🔍 Validation Features

### Smart Checking
- **File Structure**: Ensures proper Excel format
- **Data Completeness**: Checks for missing information
- **Role Permissions**: Validates grade requirements
- **User Lookup**: Cross-references with L&D data

### Error Handling
- **Clear Messages**: Simple, understandable error descriptions
- **Visual Highlighting**: Errors marked in output Excel
- **Review Options**: Detailed reports for complex issues

## 🎯 Benefits of Minimal Design

### For Users
- **Faster Learning**: Intuitive interface requires no training
- **Less Confusion**: Clear options eliminate decision fatigue  
- **Better Focus**: Minimal distractions improve task completion
- **Modern Feel**: Contemporary design feels professional

### For Productivity
- **Quick Processing**: Streamlined workflow saves time
- **Fewer Errors**: Simple interface reduces mistakes
- **Better Confidence**: Clear feedback builds user trust
- **Easy Maintenance**: Clean code is easier to update

## 🔧 Customization

### Visual Tweaks
All visual settings are in `config.py`:
- **Colors**: Modify the COLORS dictionary
- **Fonts**: Update the FONTS configuration
- **Sizing**: Adjust WINDOW_SIZE and PADDING
- **Behavior**: Change validation rules and limits

### Adding Features
The modular structure makes it easy to add features:
1. Update `config.py` for new settings
2. Add logic to appropriate module
3. Create UI components if needed
4. Test and document

## 📞 Support

### Common Issues
- **"File not found"**: Check file paths and permissions
- **"Invalid format"**: Ensure .xlsx format and proper structure  
- **Validation errors**: Review role assignments and user data
- **Permission denied**: Run with appropriate file system access

### Getting Help
1. Check the application log: `bsrs_app.log`
2. Verify configuration in `config.py`
3. Test with a single file first
4. Ensure all dependencies are installed

## 🏆 Version History

### v2.0 - Minimal Design
- ✨ Complete UI redesign with minimal aesthetics
- 🎨 Clean, modern interface with flat design
- 🚀 Simplified workflow and reduced complexity
- 📱 Responsive layout with better organization
- ⚡ Faster processing with background threading

### v1.0 - Original Version
- 📊 Basic functionality with complex interface
- 🔧 Monolithic code structure
- ⚠️ Limited error handling

## 📄 License

Internal BSRS processing tool. All rights reserved.

---

**Simple. Clean. Effective.**  
*Process your BSRS files with confidence using our minimal, modern interface.* 
