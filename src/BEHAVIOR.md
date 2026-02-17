The system has abstract User class which helps to create users 
and later Admin and Customer classes inherit from it.\
There is an abstract Service class whic helps to create services,
and classes like CloudStorageService, ConsultationService, SteamingSserivce
inherit from it and create different services.\
There are interfaces like Billable and PremiumFeature which are implemented by
CloudStorageService, ConsultationService and StreamingService.<br/>

This is how system works.