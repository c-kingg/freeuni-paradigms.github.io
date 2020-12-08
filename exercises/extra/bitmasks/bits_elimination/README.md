## EliminateBits
თქვენი დავალებაა იმპლემენტაცია გაუკეთოთ ინტერფეისში აღწერილ მეთოდს, **EliminateBits**-ს. მეთოდს გადაეცემა სამი რიცხვი: 1)num, რომლის ბიტებზეც უნდა გაკეთდეს ელიმინაცია/განულება; 2) left_boundary, ბიტების მარცხენა საზღვარი, რომლის ჩათვლითაც ხდება ელიმინაცია; 3) right_boundary, ბიტების მარჯვენა საზღვარი, რომლის ჩათვლითაც ხდება ელიმინაცია. **მაგალითი:** ```EliminateBits(25, 3, 0) დააბრუნებს 16-ს. 25-ის ბიტური ჩანაწერია 00000000 00000000 00000000 00011001. გამოძახებული ფუნქცია დააბრუნებს ესეთ რიცხვს  00000000 00000000 00000000 00010000. როგორც მაგალითიდან მიხვდით, ათვლა მარჯვენა მხრიდან იწყება, 0-დან, და ინტერვალების საზღვრებს უნდა მოიცავდეს ამოხსნა.``` 