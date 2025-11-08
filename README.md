# rpa-playwright-ui-automation
A well-organized automation framework using rpa playwright with page object model and AI Integration

Folder Structure 

/project-root
│
├── /src                     # Source code, libraries, utilities
│   ├── /pages               # Page Object classes/files (locators + methods)
│   ├── /keywords            # Custom Robot Framework keywords and utilities
│   ├── /utils               # Utility scripts (helpers, common functions)
│   └── /drivers             # Browser drivers or Playwright config files
│
├── /tests                   # Test suite files for Robot Framework and Playwright tests
│   ├── /ui                  # UI automation test cases (Robot + Playwright)
│   └── /api                 # API test cases (if any)
│
├── /resources               # Test data, configuration, environment files
│   ├── /testdata            # JSON, CSV, or other test data
│   ├── /configs             # Config files (e.g., environment, browsers)
│   └── /reports             # Test execution reports, logs, screenshots
│
├── /rpa                     # Robot Framework RPA scripts and resources
│
├── /docs                    # Documentation (usage, design decisions)
│
├── requirements.txt         # Python dependencies (Robot Framework, Playwright, etc.)
├── pytest.ini / robot.conf  # Configuration files for test runners
└── README.md                # Project overview and instructions

