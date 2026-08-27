@# Notes

Open/Closed Principle: Software entities should be open for extension but closed for modification.
Use interfaces/abstractions so new behavior can be added without repeatedly changing existing code. Strategy and Factory patterns often help.

Liskov Substitution Principle: A subtype should be usable wherever its parent type is expected without breaking correctness.
Classic warning: if Penguin extends Bird but Bird.fly() is assumed, the abstraction is probably wrong.


Single Responsibility Principle: A class should have one reason to change.
Example: Invoice should calculate invoice data, while InvoicePrinter handles formatting/printing. Avoid classes that calculate, save, email, and log all at once.

Interface Segregation Principle: Clients should not be forced to depend on methods they don't use.
Prefer small, focused interfaces such as Printer, Scanner, and FaxMachine instead of one huge Machine interface.


this repo contains notes

