TC ID	Test Case Description	Test Steps	Expected Result	Priority
UI-001	Verify chat history displays recent chats	"1. Open the application
2. Navigate to the chat history panel
3. Click on any chat
4. Verify chat opens in the middle panel"	"•  The chat history should display a list of recent chats, ordered by last interaction time.
•  Clicking a chat should load its conversation in the middle panel.
•  The selected chat should be highlighted in the left column."	High
UI-002	Check rename chat functionality	"1. Right-click on a chat
2. Select 'Rename'
3. Enter a new name and confirm
4. Verify the name updates in the chat history"	"•  The chat should update with the new name immediately.
•  The name should remain updated after refreshing the page.
•  If the name exceeds 30 characters, an error message 'Chat name too long' should appear."	Medium
UI-003	Verify delete chat option	"1. Select a chat
2. Click the 'Delete' icon
3. Confirm deletion in the pop-up
4. Check that the chat is removed"	"•  The chat should be permanently deleted from history.
•  A toast message 'Chat deleted successfully' should appear.
•  If there are no remaining chats, 'No chats available' should be displayed."	High
UI-004	Verify archive chat functionality	"1. Select a chat
2. Click the 'Archive' button
3. Navigate to 'Archived Chats' section
4. Verify chat is listed there"	"•  The chat should disappear from the active list and move to the 'Archived' section.
•  The archived chat should remain accessible under the 'Archived' tab.
•  Users should have an 'Unarchive' option."	Medium
UI-005	Verify chat search functionality	"1. Enter a keyword in the 'Search Chats' bar
2. Observe results update dynamically
3. Click on a result to open the chat"	"•  Chats containing the keyword should appear in search results.
•  Clicking a search result should load the chat in the middle panel.
•  If no matches are found, 'No results' should be displayed."	High
UI-006	Verify chat history filters (Day, Week, Month, Year)	"1. Apply different time filters to the chat history
2. Verify displayed results"	"•  Only chats from the selected timeframe should be visible.
•  If no chats exist in the selected timeframe, 'No chats found' should be displayed."	Medium
UI-007	Verify workspace creation	"1. Click 'New Workspace'
2. Enter a name, icon, and description
3. Click 'Create'
4. Verify workspace is added to the list"	"•  A new workspace should be created and listed under 'Workspaces'.
•  The workspace should persist after refreshing the page."	High
UI-008	Verify workspace switching	"1. Click on an existing workspace
2. Observe the chat session update
3. Confirm workspace-specific chat history loads"	"•  The chat area should load a different session, independent of other workspaces.
•  The left column should update with chats specific to the selected workspace."	High
UI-009	Verify workspace customization (Rename, Icon, Description)	"1. Click 'Edit Workspace'
2. Modify name, icon, or description
3. Save changes
4. Verify updates are reflected"	"•  Changes should save and be reflected immediately in the workspace list.
•  If an invalid name is entered, an error message should be displayed."	Medium
UI-010	Verify new folder/project creation	"1. Click 'New Project/Folder'
2. Enter a name and confirm
3. Verify folder appears in chat organization"	"•  A new folder should appear under chat organization.
•  The new folder should persist after refreshing the page."	Medium
UI-011	Verify adding multiple chats under a project	"1. Open a project
2. Start a new chat inside it
3. Verify the chat is grouped under the project"	"•  Chats should be grouped under the selected project.
•  Project hierarchy should be maintained."	Medium
UI-012	Verify uploading files to a project	"1. Open a project
2. Upload a file
3. Verify file is visible inside the project"	"•  The file should be stored inside the project and accessible for chats.
•  File preview should be available if supported."	High
UI-013	Verify sharing chat within the organization	"1. Select a chat
2. Click 'Share' and generate a link
3. Access the link from another device"	"•  The shared chat should be accessible to authorized users.
•  Unauthorized users should see an 'Access Denied' message."	Medium
UI-014	Verify theme switching (Dark/Light Mode)	"1. Toggle between Dark and Light mode in profile settings
2. Observe immediate UI changes"	"•  The UI theme should update instantly.
•  Theme preference should persist after logout and re-login."	Low
UI-015	Verify logout from all devices	"1. Open Profile settings
2. Click 'Logout from all devices'
3. Verify active sessions are logged out"	"•  All active sessions should be logged out.
•  User should be redirected to the login screen."	High
UI-016	Verify accessibility options (Font Size, Contrast)	"1. Open Profile settings
2. Adjust font size and contrast settings
3. Observe UI updates"	"•  UI should update according to the selected accessibility preferences.
•  Setting should persist after refresh."	Medium
UI-017	Verify deleting all chats	"1. Open Profile settings
2. Click 'Delete All Chats'
3. Confirm deletion"	"•  All chat history should be cleared permanently.
•  A warning pop-up should appear before deletion."	High
![image](https://github.com/user-attachments/assets/5c611978-744a-4fdb-a471-4fa07ab5f367)

