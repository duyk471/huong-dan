# 30 dự án Java

Mình cũng thực hiện thử thách này và đã đưa code lên Github: [`duykhanh472/luyentayjava`](https://github.com/duykhanh472/luyentayjava).

Về cơ bản là: Dùng Scanner rồi lấy kiểu như cái `*098#` của Viettel ấy, nhập số 1, 2, 3 rồi Option này kia. Mọi thứ đều là CLI và hãy dành phần lớn thời gian của bản thân để nghĩ về logic của code chứ không phải là nên làm giao diện bằng JavaFX hay Swing hay gì.

1. Simple Calculator: Use `Scanner` for input. Support `+, -, *, /` in a loop. Ask for numbers and operator, show result, repeat until user quits.
2. Number Guessing Game: Generate random number (1-100). Loop: read user guess, give "too high/low" hints. Count attempts. End when guessed correctly.
3. To-Do List Manager: Use `ArrayList<String>` for tasks. Menu: add task, list tasks, remove task, save to file, load from file. Use basic file I/O.
4. Basic Banking System: Create `Account` class with balance. Methods: `deposit`, `withdraw`, show balance. Use `ArrayList<Account>` to manage multiple accounts.
5. Student Grade Tracker: Create `Student` class (name, list of grades). Methods: `add grade`, `calculate average`, show grades. Use `ArrayList<Student>` for all students.
6. Library Book Manager: Create `Book` class (title, author, year, `isBorrowed`). Use `ArrayList<Book>`. Menu: add book, list all books, borrow book, return book, search by title/author.
7. Inventory Management System: Create `Item` class (id, name, quantity, price). Use `ArrayList<Item>`. Menu: add item, list items, update quantity, remove item, show total value.
8. Contact Book: Create `Contact` class (name, phone, email). Use `HashMap<String, Contact>` (name as key). Menu: add contact, search by name, list all, delete contact, update contact.
9. Expense Tracker with categories: Create `Expense` class (date, amount, category, description). Use `ArrayList<Expense>`. Menu: add expense, list all, show by category, total expenses, monthly summary.
10. Recipe Manager: Create `Recipe` class (name, list of ingredients, instructions). Use `ArrayList<Recipe>`. Menu: add recipe, list all recipes, search by name/ingredient, view recipe details.
11. Text File Word Counter: Read a text file using `Scanner` or `Files`. Count total words, unique words (use `HashSet`), and word frequency (`HashMap`). Display results.
12. Hangman Game: Create a list of words. Pick one randomly. Use `char` array or `StringBuilder` for hidden word. Loop: guess letter, update display, track wrong guesses. End on win or lose.
13. Rock-Paper-Scissors with stats: Play against computer (random choice). Track wins, losses, ties. Menu: play round, show statistics, reset stats.
14. Password Generator: Ask length and options (uppercase, lowercase, numbers, symbols). Generate random password using loops and `StringBuilder`. Allow multiple generations.
15. Movie Collection Organizer: Create `Movie` class (title, director, year, genre). Use `ArrayList<Movie>`. Menu: add movie, list all, search by title/genre, remove movie.
16. Simple ATM Simulation: Create `Account` class (`accountNumber`, `pin`, balance). Menu: login, check balance, `deposit`, `withdraw`, exit. Handle insufficient funds.
17. Task Scheduler: Create `Task` class (description, priority, `dueDate`). Use `ArrayList<Task>`. Menu: add task, list tasks (sorted by priority/due date), mark complete, remove task.
18. Vehicle Rental System: Create base `Vehicle` class (`licensePlate`, `model`, `rentalPrice`). Inherit `Car`, `Bike`, and `Truck` with extra fields. Use `ArrayList<Vehicle>`. Menu: add vehicle, list available, rent, return.
19. Animal Sanctuary Simulator: Create base `Animal` class (name, age) with `makeSound()` method. Inherit different animals overriding `makeSound()`. Use `ArrayList<Animal>`. Menu: add animal, list all, make all sounds.
20. Shopping Cart: Create `Item` class (name, price, quantity). Create `Cart` class with `ArrayList<Item>`. Menu: add item, remove item, list cart, calculate total.
21. Dictionary: Use `HashMap<String, String>` (word → definition). Menu: add word, search word, list all words, delete word, update definition.
22. Quiz Game with multiple question types: Create `Question` base class, inherit `MultipleChoice` and `TrueFalse`. Use `ArrayList<Question>`. Ask questions, track score, show final result.
23. Log Analyzer: Read log file line by line. Count total lines, errors (contains "ERROR"), warnings. Use `HashMap` for error type frequency. Display summary.
24. Generic Pair/Tuple class: Create generic `Pair<T, U>` class with two values. Use it to store different data types (e.g. name-age, product-price).
25. Custom Generic Stack: Implement generic `Stack<T>` class using `ArrayList`. Methods: `push`, `pop`, `peek`, `isEmpty`, `size`. Test with different types.
26. Custom Generic Queue: Implement generic `Queue<T>` class using `ArrayList`. Methods: `enqueue`, `dequeue`, `peek`, `isEmpty`, `size`. Test with different types.
27. Student Management System: Create base `Student` class, inherit `Undergraduate` and `Graduate`. Use `ArrayList<Student>`. Menu: add student, list all, show details, calculate averages.
28. Text-Based Adventure Game: Create `Room` class and `Player` (with inventory `ArrayList`). Connect rooms. Menu: go direction, take item, look, inventory.
29. File-based Note Taking App: Create `Note` class (title, content, timestamp). Use `ArrayList<Note>`. Menu: create note, list notes, view note, delete note, save/load from file.
30. Personal Finance Analyzer: Create `Transaction` class (date, amount, category, type). Use `ArrayList<Transaction>`. Menu: add transaction, list all, summaries (total income/expense, by category) using `streams`.
