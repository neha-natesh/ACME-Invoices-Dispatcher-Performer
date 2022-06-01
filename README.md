# ACME-Invoices-Dispatcher-Performer
Advance course week 1 exercise using state machine
Login to acme website and click on Invoices, then click on Search for Invoices and finally click on Display All Invoices.

Process all the invoices displayed in this menu. You should do this using Orchestrator Queues and a stand Dispatcher-Performer format. This means you should make 2 separate .xaml workflow files - one Dispatcher and one Performer.

Dispatcher - should login, scrape the data, and upload each row to the Orchestrator Queue created
Performer – should open Notepad/Word, retrieve each item from the queue, and print the details in the text editor
