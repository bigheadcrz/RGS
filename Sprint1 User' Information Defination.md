#Sprint1 User' Information Defination
2018-4-15  Linfeng Zhang

-------------------
##1 Basic Information
    {
        UserName:        String
        UserBirthYear:   Integer
        UserEducation:   String
        UserMajor:       String
        UserRank:        Int
        RankMemberSize:  Int       
    }
------
##2 Extend Information
    {
        ProjectExperience:
                { 
                     ProjectTime:
                                {
                                          TimeStart:  Integer
                                          TimeEnding: Integer
                                }

                     ProjectDescription:  String
                     UserIdentity:        String
                }
        UserKill:                String
        Self-Introduction:       String
    }

