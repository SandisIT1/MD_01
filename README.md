# MD_01
Mājasdarbs_001 (Labojums)

Izveidot jaunu Controller klasi.
Klasei jābūt nosauktai AvailabilityController.
Klasei jāsatur 2 metodes.
Pirmā metode getStatus(), bet otra setStatus().
Default-ais status, ko vajag saņemt, pirms pirmās izmaiņas ir 503 Service Unavailable
setStatus metodei jāpieņem tikai izmaiņa uz 200 OK vai 503 Service Unavailable.
setStatus() jābūt anotētai ar @PostMapping un ir jāpieņem vismaz viens @PathVariable.
