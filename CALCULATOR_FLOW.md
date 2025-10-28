# Calculator Flow Documentation

## Overview
The Cost Calculator is a multi-step form that guides users through business setup cost estimation.

## Navigation Flow

### Entry Points
All these buttons now link to `calculator/index.html`:
1. **Navigation Bar** - "Cost Calculator" button (pink/red gradient)
2. **Hero Section** - "Calculate Now" button (blue gradient)
3. **Business Setup Section** - "Calculate Now" button
4. **Mobile Menu** - "Cost Calculator" button

### Calculator Steps

**Step 1: calculator/index.html**
- Choose business activity
- Next → step2.html

**Step 2: calculator/step2.html**
- Select reason for starting business
- Previous → index.html
- Next → step3.html

**Step 3: calculator/step3.html**
- Choose business location preference
- Previous → step2.html
- Next → step4.html

**Step 4: calculator/step4.html**
- Select number of visas needed
- Previous → step3.html
- Next → step5.html

**Step 5: calculator/step5.html**
- Choose number of shareholders
- Previous → step4.html
- Next → step6.html

**Step 6: calculator/step6.html**
- Select office space requirements
- Previous → step5.html
- Next → step7.html

**Step 7: calculator/step7.html**
- Additional services selection
- Previous → step6.html
- Next → step8.html

**Step 8: calculator/step8.html**
- Banking requirements
- Previous → step7.html
- Next → step9.html

**Step 9: calculator/step9.html**
- Accounting services
- Previous → step8.html
- Next → step10.html

**Step 10: calculator/step10.html**
- PRO services
- Previous → step9.html
- Next → step11.html

**Step 11: calculator/step11.html**
- Final estimate and contact form
- Previous → step10.html
- Submit → Process form

## Features

- **Progress Tracking**: Each step shows progress
- **Data Persistence**: Form data passed through URL parameters
- **Validation**: Required fields validated before proceeding
- **Responsive Design**: Works on all devices
- **Back Navigation**: Users can go back to previous steps

## Technical Details

- Uses vanilla JavaScript for form handling
- Bootstrap for styling
- AOS for animations
- URL parameters for data transfer between steps
- Form validation on each step

## Return to Homepage

Each calculator page has a "Previous" button on step 1 that returns to `../index.html`
