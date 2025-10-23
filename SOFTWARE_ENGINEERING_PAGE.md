# Software Engineering Jobs Page

## Overview
A dedicated page for viewing and managing only Software Engineering internship positions.

## Features

### 🎯 Software Engineering Only
- Displays only jobs with category "Software Engineering"
- Filters out all other job categories (PM, Data Science, Quant Finance, Hardware)

### 📊 Dedicated Statistics
- Total Software Engineering jobs available
- Number of SWE jobs you've applied to
- Number of SWE jobs marked as not suitable
- Remaining SWE opportunities

### 🔍 Search & Filter
- Search by company name, role, or location (within SWE jobs only)
- Toggle to show/hide jobs marked as not suitable
- Pagination support (25, 50, 100, 200 items per page)

### ✅ Full Job Management
- Mark jobs as applied with timestamp tracking
- Mark jobs as not suitable
- Click on any job row to open the application link
- Export applied Software Engineering jobs

### 🧭 Navigation
- Link to return to "All Jobs" page
- Link to view "Applied Jobs" across all categories
- Logout button

## Access

### URL
Visit: `/software-engineering` or `http://localhost:3000/software-engineering`

### Navigation Links
The Software Engineering page can be accessed from:
1. **Main Page**: Click the "💻 SWE Jobs" button in the top navigation
2. **Applied Jobs Page**: Click the "💻 SWE Jobs" button in the top navigation

## UI Highlights

- **Page Title**: "💻 Software Engineering Internships"
- **Stats Cards**: Show SWE-specific metrics only
- **Clean Table View**: Removed category column (since all jobs are SWE)
- **Consistent Design**: Matches the design language of the main tracker

## Technical Details

### Files Created
1. `/app/software-engineering/page.tsx` - Next.js page route
2. `/components/SoftwareEngineeringJobs.tsx` - Main component with filtering logic

### Files Modified
1. `/components/JobTracker.tsx` - Added navigation link to SWE page
2. `/components/AppliedJobs.tsx` - Added navigation link to SWE page

### Key Differences from Main Tracker
- **Category Filter**: Hardcoded to "Software Engineering"
- **Stats**: Calculated only from Software Engineering jobs
- **Export**: Exports only SWE applied jobs
- **UI**: No category dropdown (not needed)
- **Table**: No category column (all are SWE)

## Usage

1. **Browse SWE Jobs**: View all available Software Engineering positions
2. **Search**: Use the search bar to find specific companies or roles
3. **Apply**: Click the checkbox to mark jobs as applied
4. **Not Suitable**: Click the X button to mark jobs you're not interested in
5. **Export**: Download your applied SWE jobs list
6. **Navigate**: Easily switch between All Jobs, SWE Jobs, and Applied Jobs views

## Benefits

✅ **Focused View**: See only relevant Software Engineering positions  
✅ **Faster Browsing**: No need to filter by category every time  
✅ **Dedicated Stats**: Track your SWE application progress separately  
✅ **Quick Access**: Bookmark the `/software-engineering` URL for direct access  
✅ **Same Features**: All the power of the main tracker, focused on SWE roles  

