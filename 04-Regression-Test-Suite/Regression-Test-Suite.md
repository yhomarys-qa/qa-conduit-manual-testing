# 📊 Regression Test Suite – Conduit (RealWorld App)

## 📌 Objective

This Regression Test Suite contains ALL test cases created for the Conduit (RealWorld) application, organized by module.

The goal is to ensure full functional coverage of the system, including positive, negative, boundary, and validation scenarios.

---

## 🎯 Scope

This suite covers 100% of the test cases created in the project:

- Authentication (Login & Registration)
- Articles (New Article)
- Home Page
- Settings

---

# 🔐 Authentication Module – Login

- TC-001_Access_Login_Page.md  
- TC-002_Verify_Login_Form_Elements.md  
- TC-003_Login_Valid_Email.md  
- TC-004_Login_Valid_Username.md  
- TC-005_Login_Empty_Email.md  
- TC-006_Login_Email_Case_Insensitive.md  
- TC-007_Login_Email_Placeholder.md  
- TC-008_Login_Unregistered_Email.md  
- TC-009_Login_Empty_Password.md  
- TC-010_Login_Password_Masked.md  
- TC-011_Login_Password_Placeholder.md  
- TC-012_Login_Password_Copy_Cut_Disabled.md  
- TC-013_Login_Password_Paste_Allowed.md  
- TC-014_Login_Invalid_Password.md  
- TC-015_Login_Send_One_Time_Password_Link.md  
- TC-016_Login_Forgot_Password_Link_Displayed.md  
- TC-017_Login_Forgot_Password_Link_Redirect.md  
- TC-018_Login_Button_Displayed.md  
- TC-019_Login_Using_SignIn_Button.md  
- TC-020_Login_Using_Enter_Key.md  
- TC-021_Login_Sign_Up_Link_Displayed.md  
- TC-022_Sign_Up_Link_Redirection.md
- TC-023_Authenticated_User_Redirection_From_Login_Page.md

---

# 📝 Authentication Module – Registration

- TC-001_Registration_Page_Access.md  
- TC-002_Navigation_SignUp_Link_Visibility_Accessibility.md  
- TC-003_SignUp_Page_Access_Unauthenticated_Users.md  
- TC-004_SignUp_Page_Access_via_Direct_URL.md  
- TC-005_SignUp_Page_Loads_Without_Authentication.md  
- TC-006_Registration_Page_UI_Elements_Alignment_and_Layout.md  
- TC-007_Username_Field_Visibility_on_Registration_Form.md  
- TC-008_Username_Field_Is_Required.md  
- TC-009_Username_Must_Be_Unique.md  
- TC-010_Username_Minimum_Length_Validation.md  
- TC-011_Username_Maximum_Length_Validation.md  
- TC-012_Username_Must_Start_With_Letter.md  
- TC-013_Username_Only_Latin_Letters_and_Numbers.md  
- TC-014_Username_Case_Insensitive_Validation.md  
- TC-015_Username_Invalid_Characters_Not_Allowed.md  
- TC-016_Username_Whitespace_Not_Allowed.md  
- TC-017_Email_Field_Visibility_on_Registration_Form.md  
- TC-018_Email_Field_Is_Required.md  
- TC-019_Email_Format_Validation.md  
- TC-020_Email_Must_Be_Unique.md  
- TC-021_Email_Allowed_Special_Characters.md  
- TC-022_Invalid_Email_Format_Error_Message.md  
- TC-023_Password_Field_Visibility_on_Registration_Form.md  
- TC-024_Password_Field_Is_Required.md  
- TC-025_Password_Minimum_Length_Validation.md  
- TC-026_Password_Maximum_Length_Validation.md  
- TC-027_Password_Must_Contain_Uppercase_Letter.md  
- TC-028_Password_Must_Contain_Number.md  
- TC-029_Password_Must_Contain_Special_Character.md  
- TC-030_Confirm_Password_Field_Visibility_on_Registration_Form.md  
- TC-031_Confirm_Password_Field_Is_Required.md  
- TC-032_Password_and_Confirm_Password_Must_Match.md  
- TC-033_Sign_Up_Button_Visibility.md  
- TC-034_Sign_Up_Button_Enabled_With_Valid_Data.md  
- TC-035_Sign_Up_Button_Disabled_With_Invalid_Data.md  
- TC-036_Sign_Up_Using_Enter_Key.md  
- TC-037_Successful_Registration_With_Valid_Data.md  
- TC-038_Email_Verification_Sent_After_Successful_Registration.md  
- TC-039_Email_Verification_Code_Entry.md  
- TC-040_Invalid_Email_Verification_Code_Error_Message.md  
- TC-041_Registration_Form_Reset_After_Successful_Submission.md  
- TC-042_Already_Have_An_Account_Link_Visibility.md  
- TC-043_Redirect_SignUp_To_Login.md  

---

# 📰 Articles Module – New Article

- TC-001_Access_New_Article_Page_Logged_In_User.md  
- TC-002_Access_New_Article_Page_Without_Authentication.md  
- TC-003_Article_Title_Required_Field.md  
- TC-004_Duplicate_Article_Title_Warning_Message.md  
- TC-005_Article_Title_Minimum_Length_Validation.md  
- TC-006_Article_Title_Maximum_Length_Validation.md  
- TC-007_Article_Title_Accepts_Letters.md  
- TC-008_Article_Title_Accepts_Numbers.md  
- TC-009_Article_Title_Accepts_Special_Characters.md  
- TC-010_Article_Title_No_Leading_Space.md  
- TC-011_Article_Title_No_Trailing_Space.md  
- TC-012_Article_Title_No_Multiple_Consecutive_Spaces.md  
- TC-013_Article_Description_Required_Field.md  
- TC-014_Article_Description_Minimum_Length_Validation.md  
- TC-015_Article_Description_Maximum_Length_Validation.md  
- TC-016_Article_Description_Accepts_Letters.md  
- TC-017_Article_Description_Accepts_Numbers.md  
- TC-018_Article_Description_Accepts_Special_Characters.md  
- TC-019_Article_Description_No_Leading_Space.md  
- TC-020_Article_Description_No_Trailing_Space.md  
- TC-021_Article_Description_No_Multiple_Consecutive_Spaces.md  
- TC-022_Article_Body_Required_Field.md  
- TC-023_Article_Body_Minimum_Length_Validation.md  
- TC-024_Article_Body_Maximum_Length_Validation.md  
- TC-025_Article_Body_Accepts_Letters.md  
- TC-026_Article_Body_Accepts_Numbers.md  
- TC-027_Article_Body_Accepts_Special_Characters.md  
- TC-028_Article_Body_No_Leading_Space.md  
- TC-029_Article_Body_No_Trailing_Space.md  
- TC-030_Article_Body_No_Multiple_Consecutive_Spaces.md  
- TC-031_Article_Body_Does_Not_Accept_Attachments.md  
- TC-032_Article_Body_Text_Area_Is_Resizable.md  
- TC-033_Tags_Field_Is_Optional.md  
- TC-034_Add_Valid_Tag.md  
- TC-035_Tag_Minimum_Length_Validation.md  
- TC-036_Tag_Maximum_Length_Validation.md  
- TC-037_Tag_Must_Start_With_Hash.md  
- TC-038_Tag_Allows_Only_Alphanumeric_After_Hash.md  
- TC-039_Tags_Are_Case_Insensitive.md  
- TC-040_Tag_Minimum_Number_of_Tags.md  
- TC-041_Maximum_Number_of_Tags_Limit.md  
- TC-042_User_Can_Create_Tags_For_Article.md  
- TC-043_Duplicate_Tags_Should_Not_Be_Allowed.md  
- TC-044_Filter_Articles_By_Tag.md  

---

# 🏠 Home Module

- TC-001_Home_Access_via_Logo.md  
- TC-002_Home_Access_via_Header_Inicio.md  
- TC-003_Home_Banner_Text_and_Background.md  
- TC-004_Feed_Tabs_Visible_for_Logged_User.md  
- TC-005_Seu_Feed_Empty_By_Default.md  
- TC-006_Seu_Feed_Shows_Followed_Users_Articles.md  
- TC-007_Feed_Global_Visible_for_Guest.md  
- TC-008_Feed_Global_Shows_All_Articles.md  
- TC-009_Feed_Global_Ordered_By_Recent.md  
- TC-010_Pagination_Displays_Max_10_Articles_Per_Page.md  
- TC-011_Pagination_Navigation_Between_Pages.md  
- TC-012_Pagination_Page_Range_Display.md  
- TC-013_Article_Author_Avatar_and_Username_Display.md  
- TC-014_Article_Creation_Date_Format.md  
- TC-015_Article_Title_Display.md  
- TC-016_Article_Description_Display.md  
- TC-017_Article_Read_More_Link_Display.md  
- TC-018_Article_Like_Button_Display.md  
- TC-019_Navigate_to_Author_Profile_via_Username.md  
- TC-020_Navigate_to_Article_via_Title.md  
- TC-021_Navigate_to_Article_via_Description.md  
- TC-022_Navigate_to_Article_via_Read_More_Link.md  
- TC-023_Likes_Visible_for_Logged_User.md  
- TC-024_Likes_Not_Visible_for_Guest_User.md  
- TC-025_User_Can_Like_Article.md  
- TC-026_User_Cannot_Like_Same_Article_Multiple_Times.md  
- TC-027_User_Can_Unlike_Article.md  
- TC-028_Tags_Populares_Position_Right_of_Feed.md  
- TC-029_Filter_Articles_By_Tag.md  
- TC-030_Selected_Tag_Is_Highlighted.md  

---

# ⚙️ Settings Module

- TC-001_Access_Settings_Page.md  
- TC-002_Edit_Profile_Information.md  
- TC-003_Save_Profile_Changes.md  
- TC-004_Update_Single_Field.md  
- TC-005_Settings_Tab_Visible_For_Logged_User.md  
- TC-006_Settings_Tab_Not_Visible_For_Logged_Out_User.md  
- TC-007_Navigate_To_Settings_From_Header.md  
- TC-008_Redirect_Unauthenticated_User_To_Login.md  
- TC-009_No_Settings_Content_Exposure.md  
- TC-010_Required_Fields_Visible.md  
- TC-011_Username_Mandatory.md  
- TC-012_Username_Unique.md  
- TC-013_Username_Min_Length.md  
- TC-014_Username_Max_Length.md  
- TC-015_Username_Valid_Characters.md  
- TC-016_Username_Starts_With_Letter.md  
- TC-017_Username_No_Special_Characters.md  
- TC-018_Username_No_NonPrintable_Characters.md  
- TC-019_Username_Case_Insensitive.md  
- TC-020_Email_Mandatory.md  
- TC-021_Email_Valid_Format.md  
- TC-022_Email_Name_Part_Allows_Letters_And_Numbers.md  
- TC-023_Email_Name_Part_Allows_Valid_Special_Characters.md  
- TC-024_Email_Must_Be_Unique.md  
- TC-025_Optional_Fields_Visible.md  
- TC-026_Profile_Picture_URL_Optional.md  
- TC-027_Profile_Picture_URL_Valid_Link.md  
- TC-028_Profile_Picture_URL_Invalid_Value.md  
- TC-029_Bio_Optional.md  
- TC-030_Bio_Min_Length_Behavior.md  
- TC-031_Bio_Max_Length.md  
- TC-032_Bio_Accepts_Letters.md  
- TC-033_Bio_Accepts_Numbers.md  
- TC-034_Bio_Accepts_Special_Characters.md  
- TC-035_Bio_Accepts_Spaces.md  
- TC-036_Bio_Leading_Spaces_Behavior.md  
- TC-037_Bio_Trailing_Spaces_Behavior.md  
- TC-038_Bio_Consecutive_Spaces_Behavior.md  
- TC-039_New_Password_Optional.md  
- TC-040_New_Password_Must_Differ_From_Old.md  
- TC-041_New_Password_Min_Length.md  
- TC-042_New_Password_Max_Length.md  
- TC-043_New_Password_Accepts_Letters.md  
- TC-044_New_Password_Requires_Uppercase.md  
- TC-045_New_Password_Accepts_Numbers.md  
- TC-046_New_Password_Requires_Number.md  
- TC-047_New_Password_Accepts_Special_Characters.md  
- TC-048_New_Password_Requires_Symbol.md  
- TC-049_New_Password_Input_Is_Masked.md  
- TC-050_Update_Settings_With_Valid_Data.md  
- TC-051_Update_Settings_Validates_Mandatory_Fields.md  
- TC-052_Settings_Data_Persistence_After_Update.md  
- TC-053_Profile_Picture_Updates_After_Save.md  
- TC-054_Profile_Picture_Position_In_Header.md  
- TC-055_Profile_Picture_Not_Updated_When_Unchanged.md  
- TC-056_Username_Updated_Display_After_Save.md  
- TC-057_Username_Displayed_In_Header.md  
- TC-058_Username_Not_Updated_When_Unchanged.md  
- TC-059_Bio_Updated_Display_After_Save.md  
- TC-060_Bio_Displayed_Below_Username.md  
- TC-061_Bio_Not_Updated_When_Unchanged.md  
- TC-062_Login_With_Updated_Email_Successfully.md  
- TC-063_Session_Remains_Valid_After_Email_Update.md  
- TC-064_Login_With_Old_Email_Should_Fail.md  
- TC-065_Login_Shows_Invalid_Credentials_Message_For_Old_Email.md  
- TC-066_Login_With_New_Password_Successfully.md  
- TC-067_Login_With_Old_Password_Should_Fail.md  
- TC-068_Login_With_Old_Password_Shows_Generic_Error.md  
- TC-069_Logout_Button_Is_Visible_On_Settings_Page.md  
- TC-070_Logout_Button_Position_On_Settings_Page.md  
- TC-071_Logout_Redirects_User_To_Home_Page.md  
- TC-072_User_Session_Is_Terminated.md  

---

## 🚪 Entry Criteria

- Application is available and stable  
- Test data is prepared  
- Authentication is working  

---

## 🚪 Exit Criteria

- All test cases executed  
- All major defects identified  
- System stability confirmed after regression cycle  
