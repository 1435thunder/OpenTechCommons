🎬 Scene Director Add-on for Blender

A cross-platform Blender add-on for organizing film productions inside .blend projects. Developed as part of the Echoes in Ice toolchain and published under the OpenTechCommons initiative.
🔧 Features (v0.3)

    📁 Create and manage scene/take folder structures per film
    📝 Markdown note editor with real-time preview
    🖼 Reference image viewer with scale control
    💡 Save and recall camera + lighting snapshots
    🕒 Timeline bookmarks for scene takes
    📂 Open project folders in file explorer (Windows/macOS/Linux)
    🧠 [Optional] Local Ollama integration for scene prompt → shot list
    🔐 Overwrite protection + scene/take validation
    📋 Copy full notes and metadata to clipboard
    🧠 Designed for modular upgrade path (v0.3.1+ will include drag-drop, live folder asset view)

🚀 Installation

    Download the latest ZIP (scene_director_v0.3.zip)
    Open Blender → Edit → Preferences → Add-ons → Install...
    Enable Scene Director
    Use the Scene Director tab in the Sidebar (N-Panel)

📁 Folder Structure Example

/MyBlendProject/

├── MyFilm.blend

└── SpaceOdyssey/

└── scenes/

└── S01_Intro/

└── takes/

└── T01/

├── notes.md

├── ref_image.jpg

├── cam_snapshot_01.json

└── scene.meta.json
🤖 Ollama Integration

    Prompts like: “Describe this moonlit ice canyon scene”
    Automatically returns shot breakdown or scene summary
    Runs locally via Ollama API (localhost:11434)
    Optional & fail-safe

📈 Roadmap

    v0.3.1: drag-and-drop asset linking, folder snapshot viewer, markdown preview of notes
    v0.4: visual storyboard + frame tagging, dialog generation, character tracking

🧠 Origin

Developed with @1435thunder as part of the Echoes In Ice Blender workflow for planetary-scale creative production.

MIT License • Contributions Welcome • AI-Compatible
