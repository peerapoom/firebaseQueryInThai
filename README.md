# firebaseQueryInThai
#For asking pro about how to query firebase database in Thai language (Swift2.2 iOS + Firebase realtime database)
  When I query in English or Number charactor such as "region" or "dbversion". The Firebase database return correct value in snapshot very well that's awesome but when I query some parameter in Thai language such as "ปางมะค่าวิทยาคม KPT" in key "lookup" The Firebase database cannot find the record in database and return "nil" because in snapshot it recognize as "\U0e1b\U0e32\U0e07\U0e21\U0e30\U0e04\U0e48\U0e32\U0e27\U0e34\U0e17\U0e22\U0e32\U0e04\U0e21\U000a" which is unicode charactor different from "ปางมะค่าวิทยาคม" so that it returned "nil" or "null" as a query result.
  
