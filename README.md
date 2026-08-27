@# Notes

Open/Closed Principle: Software entities should be open for extension but closed for modification.
Use interfaces/abstractions so new behavior can be added without repeatedly changing existing code. Strategy and Factory patterns often help.




Single Responsibility Principle: A class should have one reason to change.
Example: Invoice should calculate invoice data, while InvoicePrinter handles formatting/printing. Avoid classes that calculate, save, email, and log all at once.


this repo contains notes

