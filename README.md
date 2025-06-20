# IamResponding Schedule Viewer

Browser bookmarklet for IamResponding.com coordinators. Displays 7-day schedules in 15-minute blocks with color-coded crew validation.

## Color Coding

- 🔴 **Red**: No personnel
- 🟡 **Yellow**: Incomplete crew (1 person, 2 people both starting with "R", or all identifiers ending with "N")
- 🟢 **Green**: Valid crew (2-4 people with proper mix)
- 🟣 **Purple**: Invalid crew (5+ people)

## Installation

### Chrome
1. Show bookmarks bar: `Ctrl+Shift+B` (Windows) or `Cmd+Shift+B` (Mac)
2. Right-click bookmarks bar → "Add page..."
3. Name: `IAR Schedule Viewer`
4. URL: Copy contents from `iar_bookmarklet.txt`

### Firefox
1. Show bookmarks toolbar: View → Toolbars → Bookmarks Toolbar
2. Right-click toolbar → "Add Bookmark..."
3. Name: `IAR Schedule Viewer`
4. Location: Copy contents from `iar_bookmarklet.txt`

## Usage

1. Login to dashboard.iamresponding.com
2. Click the bookmarklet
3. Use navigation buttons to browse weeks
4. Click "Jump to Now" to find current time

## Features

- 15-minute time blocks (00:00-23:45)
- Filters out Unavailable/O.O.T./Officer On-Call personnel
- EST timezone display
- Past time indicators (diagonal stripes)
- Week navigation
- Cross-day shift support

## Requirements

- Active IamResponding coordinator session
- Chrome or Firefox browser