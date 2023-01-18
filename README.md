# VehicleDet-MVC-

ეს საიტი განკუთვნილია მანქანების ტექნიკური ინფორმაციის მისაღებად:

1)პროექტის გაშვებისას პირველრიგში ხდება აუთენთიფიკაცია(სურათი 1), 
2)რომლის გავლის შემდეგაც მომხმარებელს შეეძლება მანქანების სიის ნახვა(სურათი 12), 
3)ბაზას გაწერილი აქვს როლები(User,Admin) შესაბამისად იუსერს შეუძლია მხოლოდ მანქანებიის სიის მეთოდის გამოყენება, ხოლო ადმინს ყველა მეთოდის(სურათი  15,16),
4)ადმინის პრივილეგიებით შესვლის შემთხვევაში ადმინს ექნება შემდეგ მეთოდებზე წვდომა(Crud ოპერაციები):
	1.მანქანის დამატება(CarAdd)(სურათი 2)
	2.მანქანების სიის ნახვა(ViewVehicles)(სურათი 3)
	3.მანქანის წაშლა(CarDelete)(სურათი 4)
	4.წაშლილი მანქანების სიის ნახვა(DeleteView)(სურათი 5)
	5.წაშლილი მანქანის აღდგენა(CarRecover)(სურათი 6)
	6.მანქანის პარამეტრების შეცვლა როგორც მანქანების სიიდან ასევე წაშლილი მანქანების სიიდან(CarUpdate)(სურათი 7,8)
5)შესულ მომხმარებელს შეუძლია პაროლის შეცვლა(სურათი 9,10)
6)იუზერის პრივილეგიებით შესვლის შემთხვევაში გაიხსნება ViewVehicles მეთოდი(სურათი 11,12)
7)ახალი მომხმარებლის რეგისტრაცია(სურათი 13,14)

მომხმარებელი რეგისტრაციის გავლის შემდეგ ვარდება ბაზაში სადაც ინახება მისი Id,Email და ჰეშირებული პაროლი, 
დაცულია მეილის უნიკალურობა და პაროლს აქვს შეზღუდვები დადებული. მანქანის დამატებისას ასევე დადებულია შეზღუდვები მოდელში.
წაშლილი მანქანა ინახება ცალკე ცხრილში რომლიდანაც შემდგომში მთავარ ცხრილში გადატანა (აღდგენა) შესაძლებელია.

გამოყენებულია(C#,Javascript, SQL(Dapper), Bootstrap)
