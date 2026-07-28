# Deskbuddy with Notion integration into Notes page
Deskbuddy is a compact ESP32-based smart desk companion built around a touchscreen display. The project combines 3D printing, simple hardware, and software to turn a raw ESP32 screen into a practical mini dashboard for your workspace. It is designed to be easy to set up and easy to personalize.
This is a fork of the original Deskbuddy project; this version integrates a Notion tasks page into the Notes page of the CYD.
# Setup
The only changes you need to do except the setup guide is that you need to add the notion page
id<img width="532" height="31" alt="image" src="https://github.com/user-attachments/assets/5ab74206-8933-48a5-9a7e-7231e5014970" />

(highlighted part of the url)

place that 32 character code into the NOTION_PAGE_ID = "YOUR_PAGE_ID"; line

and you need to generate an API key on the Notion Integrations page(notion.so/my-integrations)... starts with ntn_ or secret_ 
place that into the NOTION_SECRET = "YOUR_NOTION_SECRET"; line
