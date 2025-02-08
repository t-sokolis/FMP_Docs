Here's a structured guide for implementing **theme style naming best practices** in **FileMaker**.

---

# **FileMaker Theme & Style Naming Guide**

## **1. Why Use a Naming Convention?**
A clear and structured naming system helps:
✅ Ensure consistency across layouts  
✅ Simplify maintenance & updates  
✅ Improve collaboration between developers  
✅ Speed up theme modifications  

---

## **2. FileMaker Theme Naming**
### **Best Practices**
1. **Use descriptive names**  
   - Good: `CRM_LightMode`, `Corporate_Dark`, `POS_Kiosk`  
   - Bad: `Theme1`, `Test_Theme`, `Default`  

2. **Consider project context**  
   - Include the system or function:  
     - `RetailPOS_Dark` (Point of Sale)  
     - `HR_Portal_Light` (Human Resources System)  

3. **Keep it future-proof**  
   - Avoid dates (`Theme2023`) unless versioning is needed  
   - Use versioning if necessary:  
     - `Corporate_Dark_v2`  

---

## **3. FileMaker Style Naming**
Each style applies to **text, fields, buttons, tabs, popovers**, etc. Naming should reflect **category, size, weight, and state**.

### **3.1 Text Styles**
Use prefixes to organize:
- `Text_` for body text  
- `Label_` for form labels & headings  

**Example Naming:**
| Name | Use Case |
|---|---|
| `Text_Body_14` | Standard body text (14px) |
| `Text_Body_16_Bold` | Larger bold text |
| `Label_Heading_24_Bold` | Page headings |
| `Label_Form_12` | Labels for input fields |
| `Text_Body_14_Disabled` | Disabled text |

---

### **3.2 Field Styles**
For input fields, define **type, size, and state**.

**Example Naming:**
| Name | Use Case |
|---|---|
| `Field_Input_Default` | Standard input field |
| `Field_SearchBox` | Search bar styling |
| `Field_Input_Disabled` | Non-editable fields |
| `Field_Dropdown` | Styled dropdown fields |
| `Field_Input_Error` | Validation error state |

---

### **3.3 Button Styles**
Prefix buttons with `Btn_` and indicate their **type and state**.

**Example Naming:**
| Name | Use Case |
|---|---|
| `Btn_Primary` | Main action buttons |
| `Btn_Secondary` | Secondary actions |
| `Btn_Outline` | Outline-styled buttons |
| `Btn_Primary_Hover` | Hover state |
| `Btn_Primary_Disabled` | Disabled state |

---

### **3.4 Tab Panel & Popover Styles**
Tabs and popovers should have clear, contextual names.

**Example Naming:**
| Name | Use Case |
|---|---|
| `Tab_Navigation` | Main navigation tabs |
| `Tab_Secondary` | Secondary-level tabs |
| `Popover_Info` | Popover for additional info |
| `Popover_Warning` | Alert-style popover |

---

## **4. Best Practices for Implementation**
✅ **Create a Style Guide Document** → Keep all naming conventions documented  
✅ **Group Similar Styles** → Organize styles in categories inside FileMaker  
✅ **Avoid Overlapping Names** → Be specific (`Field_Input_Default` vs. `Field_SearchBox`)  
✅ **Use Versioning for Updates** → Example: `Btn_Primary_v2`  

---

### **5. Bonus: Naming Convention Cheatsheet**
| Prefix | Category |
|---|---|
| `Text_` | Body text styles |
| `Label_` | Labels and headings |
| `Field_` | Input fields |
| `Btn_` | Buttons |
| `Tab_` | Tab panels |
| `Popover_` | Popovers & overlays |

---

This structure will keep your **FileMaker themes & styles scalable, maintainable, and easy to use**. Would you like a downloadable reference or a FileMaker demo file with pre-set styles?
