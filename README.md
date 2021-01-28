# Get.JIRA-USersDetailsFromGroup
//The routine : GetUsersDetailFromGroup returns a list of objects (objects of type Group) List<GroupInfo>
        // & write result to file (Json style) : List-Details-from-group-{0}.txt" 
        // & write result to file (text file)  : List-accounts-from-group-{0}.txt"
        // Details are : username, full name, email, group , active user or not
        //---------------------------------------------------------------------------------------------------
        public static async Task<List<GroupInfo>> GetUSersDetailFromGroup(string username, string password, string urlbase, string group)
        
