Banner System
The application features a dynamic banner system that displays at the bottom of the interface during two key stages of the user journey: the Enter Round page and the final End of Round Scorecard.

Purpose of Banners
The banner system is designed to provide space for community highlights or localized advertisements. The current implementation includes a mix of organizational branding and sport-specific content, featuring:

Range Logos: Koteewi Archery Range and the Hoosier Traditional Archers.

Themed Content: Eight unique archery-related quotes and sayings.

These slots can be easily customized or replaced to support sponsorship ads, club announcements, or upcoming event reminders.

Logic: The app randomly selects one of 10 available banners for each display.

File Requirements: Files must be named sequentially: banner1.jpg through banner10.jpg.

Dimensions: Banners are optimized for 800px × 133px.

Fail-Safe Handling: If the app cannot find the randomly selected banner, it defaults to banner1.jpg. If banner1.jpg is also unavailable, the banner section will be hidden to prevent broken image icons from appearing.


Visual Style

To maintain UI consistency, the following color palette is used:

Element...........Hex Code.........Purpose

Background.....#0f172a.......Main Application Canvas (Dark Blue)

Banner Text.....#f8fafc..........High-contrast readability (Off-White)

Text Stroke......#1e293b.......Visual separation/depth (Slate Blue)
