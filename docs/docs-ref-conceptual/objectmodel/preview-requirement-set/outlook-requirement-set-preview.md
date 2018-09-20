# <a name="outlook-add-in-api-preview-requirement-set"></a><span data-ttu-id="e64c7-101">Preview-Anforderungssatz für die Outlook-Add-In-API</span><span class="sxs-lookup"><span data-stu-id="e64c7-101">Outlook add-in API Preview requirement set</span></span>

<span data-ttu-id="e64c7-102">Die Outlook-Add-In-API-Teilmenge der JavaScript-API für Office umfasst Objekte, Methoden, Eigenschaften und Ereignisse, die Sie in Outlook-Add-Ins verwenden können.</span><span class="sxs-lookup"><span data-stu-id="e64c7-102">The Outlook add-in API subset of the JavaScript API for Office includes objects, methods, properties and events that you can use in an Outlook add-in.</span></span>

> [!NOTE]
> <span data-ttu-id="e64c7-103">Diese Dokumentation ist für eine **Vorschau** [Anforderung festgelegt](/javascript/office/requirement-sets/outlook-api-requirement-sets).</span><span class="sxs-lookup"><span data-stu-id="e64c7-103">This documentation is for a **preview** [requirement set](/javascript/office/requirement-sets/outlook-api-requirement-sets).</span></span> <span data-ttu-id="e64c7-104">Dieser Anforderungssatz ist noch nicht vollständig implementiert. Daher melden Clients die Unterstützung für diesen Anforderungssatz nicht korrekt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-104">This requirement set is not fully implemented yet, and clients will not accurately report support for it.</span></span> <span data-ttu-id="e64c7-105">Sie sollten diesen Anforderungssatz nicht im Manifest Ihres Add-Ins angeben.</span><span class="sxs-lookup"><span data-stu-id="e64c7-105">You should not specify this requirement set in your add-in manifest.</span></span> <span data-ttu-id="e64c7-106">Methoden und Eigenschaften, die in diesem Anforderungssatz eingeführt werden, sollten vor der Verwendung einzeln auf ihre Verfügbarkeit getestet werden.</span><span class="sxs-lookup"><span data-stu-id="e64c7-106">Methods and properties that are introduced in this requirement set should be individually tested for availability before using them.</span></span>

<span data-ttu-id="e64c7-107">Die Preview-Anforderungssatz enthält alle Features von [Anforderung 1.6 festgelegt](../requirement-set-1.6/outlook-requirement-set-1.6.md).</span><span class="sxs-lookup"><span data-stu-id="e64c7-107">The Preview Requirement set includes all of the features of [Requirement set 1.6](../requirement-set-1.6/outlook-requirement-set-1.6.md).</span></span>

## <a name="features-in-preview"></a><span data-ttu-id="e64c7-108">Preview-Funktionen</span><span class="sxs-lookup"><span data-stu-id="e64c7-108">Features in preview</span></span>

<span data-ttu-id="e64c7-109">Die folgenden Funktionen haben aktuell noch Preview-Status:</span><span class="sxs-lookup"><span data-stu-id="e64c7-109">The following features are in preview.</span></span>

- <span data-ttu-id="e64c7-110">[Von](/javascript/api/outlook/office.from) - hinzugefügt ein neues Objekt, das bietet eine Methode zum Abrufen der vom Wert.</span><span class="sxs-lookup"><span data-stu-id="e64c7-110">[From](/javascript/api/outlook/office.from) - Added a new object that provides a method to get the from value.</span></span>
- <span data-ttu-id="e64c7-111">[Organizer](/javascript/api/outlook/office.organizer) - hinzugefügt, ein neues Objekt, das eine Methode zum Abrufen des Werts der Organisator bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-111">[Organizer](/javascript/api/outlook/office.organizer) - Added a new object that provides a method to get the organizer value.</span></span>
- <span data-ttu-id="e64c7-112">[Serie](/javascript/api/outlook/office.recurrence) - hinzugefügt, ein neues Objekt, das Methoden zum Abrufen und festlegen das Serienmuster von Terminen jedoch nur das Serienmuster von Nachrichten, die Anfragen meeting sind get bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-112">[Recurrence](/javascript/api/outlook/office.recurrence) - Added a new object that provides methods to get and set the recurrence pattern of appointments but only get the recurrence pattern of messages that are meeting requests.</span></span>
- <span data-ttu-id="e64c7-113">[SeriesTime](/javascript/api/outlook/office.seriestime) - hinzugefügt, ein neues Objekt, das Methoden zum Abrufen und Festlegen von Datum und Uhrzeit der Termine in einer Terminserie und zum Abrufen der Daten und Uhrzeiten von Besprechungsanfragen in einer Terminserie bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-113">[SeriesTime](/javascript/api/outlook/office.seriestime) - Added a new object that provides methods to get and set the dates and times of appointments in a recurring series and to get the dates and times of meeting requests in a recurring series.</span></span>
- <span data-ttu-id="e64c7-p102">[Event.Completed](/javascript/api/office/office.addincommands.event#completed-options-): ein neuer optionaler Parameter `options`, bei dem es sich um ein Wörterbuch mit einem einzigen gültigen Wert handelt, und zwar `allowEvent`. Dieser Wert wird verwendet, um die Ausführung eines Ereignisses abzubrechen.</span><span class="sxs-lookup"><span data-stu-id="e64c7-p102">[Event.completed](/javascript/api/office/office.addincommands.event#completed-options-) - A new optional parameter `options`, which is a dictionary with one valid value `allowEvent`. This value is used to cancel execution of an event.</span></span>
- <span data-ttu-id="e64c7-116">[Office.context.mailbox.item.addFileAttachmentFromBase64Async](office.context.mailbox.item.md#addfileattachmentfrombase64asyncbase64file-attachmentname-options-callback) - hinzugefügt, eine neue Methode, die eine Datei von base64-Codierung auf einer Nachricht oder eines Termins anfügt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-116">[Office.context.mailbox.item.addFileAttachmentFromBase64Async](office.context.mailbox.item.md#addfileattachmentfrombase64asyncbase64file-attachmentname-options-callback) - Added a new method that attaches a file from the base64 encoding to a message or appointment.</span></span>
- <span data-ttu-id="e64c7-117">[Office.context.mailbox.item.addHandlerAsync](office.context.mailbox.item.md#addhandlerasynceventtype-handler-options-callback) - hinzugefügt, eine neue Methode, die einen Ereignishandler für ein Ereignis unterstützte hinzufügt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-117">[Office.context.mailbox.item.addHandlerAsync](office.context.mailbox.item.md#addhandlerasynceventtype-handler-options-callback) - Added a new method that adds an event handler for a supported event.</span></span>
- <span data-ttu-id="e64c7-118">[Office.context.mailbox.item.from](office.context.mailbox.item.md#from-emailaddressdetailsjavascriptapioutlookofficeemailaddressdetailsfromjavascriptapioutlookofficefrom) - geändert, zum Abrufen der Wert im Modus "Verfassen".</span><span class="sxs-lookup"><span data-stu-id="e64c7-118">[Office.context.mailbox.item.from](office.context.mailbox.item.md#from-emailaddressdetailsjavascriptapioutlookofficeemailaddressdetailsfromjavascriptapioutlookofficefrom) - Modified to get the from value in Compose mode.</span></span>
- <span data-ttu-id="e64c7-119">[Office.context.mailbox.item.getInitializationContextAsync](office.context.mailbox.item.md#getinitializationcontextasyncoptions-callback) – Neue Funktion hinzugefügt, die Initialisierungsdaten zurückgibt, die übergeben werden, wenn das Add-In [durch eine Nachricht mit Aktionen aktiviert](https://docs.microsoft.com/outlook/actionable-messages/invoke-add-in-from-actionable-message) wird.</span><span class="sxs-lookup"><span data-stu-id="e64c7-119">[Office.context.mailbox.item.getInitializationContextAsync](office.context.mailbox.item.md#getinitializationcontextasyncoptions-callback) - Added a new function that returns initialization data passed when the add-in is [activated by an actionable message](https://docs.microsoft.com/outlook/actionable-messages/invoke-add-in-from-actionable-message).</span></span>
- <span data-ttu-id="e64c7-120">[Office.context.mailbox.item.organizer](office.context.mailbox.item.md#organizer-emailaddressdetailsjavascriptapioutlookofficeemailaddressdetailsorganizerjavascriptapioutlookofficeorganizer) - so geändert, dass der Organisator Wert im Modus "Verfassen" abgerufen.</span><span class="sxs-lookup"><span data-stu-id="e64c7-120">[Office.context.mailbox.item.organizer](office.context.mailbox.item.md#organizer-emailaddressdetailsjavascriptapioutlookofficeemailaddressdetailsorganizerjavascriptapioutlookofficeorganizer) - Modified to get the organizer value in Compose mode.</span></span>
- <span data-ttu-id="e64c7-121">[Office.context.mailbox.item.recurrence](office.context.mailbox.item.md#nullable-recurrence-recurrencejavascriptapioutlookofficerecurrence) - hinzugefügt, eine neue Eigenschaft, die Ruft ab oder legt ein Objekt, das Methoden zum Verwalten von des Serienmusters der ein Terminelement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-121">[Office.context.mailbox.item.recurrence](office.context.mailbox.item.md#nullable-recurrence-recurrencejavascriptapioutlookofficerecurrence) - Added a new property that gets or sets an object which provides methods to manage the recurrence pattern of an appointment item.</span></span> <span data-ttu-id="e64c7-122">Diese Eigenschaft kann auch verwendet werden, um das Serienmuster einer Besprechung abzurufen Element Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e64c7-122">This property can also be used to get the recurrence pattern of a meeting request item.</span></span>
- <span data-ttu-id="e64c7-123">[Office.context.mailbox.item.removeHandlerAsync](office.context.mailbox.item.md#removehandlerasynceventtype-handler-options-callback) - hinzugefügt, eine neue Methode, die einen Ereignishandler entfernt wird.</span><span class="sxs-lookup"><span data-stu-id="e64c7-123">[Office.context.mailbox.item.removeHandlerAsync](office.context.mailbox.item.md#removehandlerasynceventtype-handler-options-callback) - Added a new method that removes an event handler.</span></span>
- <span data-ttu-id="e64c7-124">[Office.context.mailbox.item.seriesId](office.context.mailbox.item.md#nullable-seriesid-string) - hinzugefügt, dass eine neue Eigenschaft, die die Id der Datenreihe Auftreten eines Serientermins versehen gehört.</span><span class="sxs-lookup"><span data-stu-id="e64c7-124">[Office.context.mailbox.item.seriesId](office.context.mailbox.item.md#nullable-seriesid-string) - Added a new property that gets the id of the series an occurrence belongs to.</span></span>
- <span data-ttu-id="e64c7-125">[Office.context.auth.getAccessTokenAsync](https://docs.microsoft.com/office/dev/add-ins/develop/sso-in-office-add-ins#sso-api-reference) – Zugriff auf `getAccessTokenAsync` wurde hinzugefügt, wodurch Add-Ins [ein Zugriffstoken für die Microsoft Graph-API erhalten](https://docs.microsoft.com/outlook/add-ins/authenticate-a-user-with-an-sso-token).</span><span class="sxs-lookup"><span data-stu-id="e64c7-125">[Office.context.auth.getAccessTokenAsync](https://docs.microsoft.com/office/dev/add-ins/develop/sso-in-office-add-ins#sso-api-reference) - Added access to `getAccessTokenAsync`, which allows add-ins to [get an access token](https://docs.microsoft.com/outlook/add-ins/authenticate-a-user-with-an-sso-token) for the Microsoft Graph API.</span></span>
- <span data-ttu-id="e64c7-126">[Office.MailboxEnums.Days](/javascript/api/outlook/office.mailboxenums.days) - hinzugefügt, eine neue Enumeration, die den Tag der Woche oder Typ des Tages angibt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-126">[Office.MailboxEnums.Days](/javascript/api/outlook/office.mailboxenums.days) - Added a new enum that specifies the day of week or type of day.</span></span>
- <span data-ttu-id="e64c7-127">[Office.MailboxEnums.Month](/javascript/api/outlook/office.mailboxenums.month) - hinzugefügt, eine neue Enumeration, die den Monat angibt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-127">[Office.MailboxEnums.Month](/javascript/api/outlook/office.mailboxenums.month) - Added a new enum that specifies the month.</span></span>
- <span data-ttu-id="e64c7-128">[Office.MailboxEnums.RecurrenceTimeZone](/javascript/api/outlook/office.mailboxenums.recurrencetimezone) - hinzugefügt, eine neue Enumeration, die angibt, die Zeitzone auf die Serie angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="e64c7-128">[Office.MailboxEnums.RecurrenceTimeZone](/javascript/api/outlook/office.mailboxenums.recurrencetimezone) - Added a new enum that specifies the time zone applied to the recurrence.</span></span>
- <span data-ttu-id="e64c7-129">[Office.MailboxEnums.RecurrenceType](/javascript/api/outlook/office.mailboxenums.recurrencetype) - hinzugefügt, eine neue Enumeration, die den Typ des Serienmusters angibt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-129">[Office.MailboxEnums.RecurrenceType](/javascript/api/outlook/office.mailboxenums.recurrencetype) - Added a new enum that specifies the type of recurrence.</span></span>
- <span data-ttu-id="e64c7-130">[Office.MailboxEnums.WeekNumber](/javascript/api/outlook/office.mailboxenums.weeknumber) - hinzugefügt, eine neue Enumeration, die die Woche des Monats angibt.</span><span class="sxs-lookup"><span data-stu-id="e64c7-130">[Office.MailboxEnums.WeekNumber](/javascript/api/outlook/office.mailboxenums.weeknumber) - Added a new enum that specifies the week of the month.</span></span>
- <span data-ttu-id="e64c7-131">[Office.EventType](/javascript/api/office/office.eventtype) - geändert zur Unterstützung von RecurrenceChanged, RecipientsChanged, AppointmentTimeChanged und OfficeThemeChanged Ereignisse durch Hinzufügen von `RecurrencePatternChanged`, `RecipientsChanged`, `AppointmentTimeChanged`, und `OfficeThemeChanged` Einträge fest.</span><span class="sxs-lookup"><span data-stu-id="e64c7-131">[Office.EventType](/javascript/api/office/office.eventtype) - Modified to support RecurrenceChanged, RecipientsChanged, AppointmentTimeChanged, and OfficeThemeChanged events through addition of `RecurrencePatternChanged`, `RecipientsChanged`, `AppointmentTimeChanged`, and `OfficeThemeChanged` entries respectively.</span></span>

## <a name="see-also"></a><span data-ttu-id="e64c7-132">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="e64c7-132">See also</span></span>

- [<span data-ttu-id="e64c7-133">Outlook-Add-Ins</span><span class="sxs-lookup"><span data-stu-id="e64c7-133">Outlook add-ins</span></span>](https://docs.microsoft.com/outlook/add-ins/)
- [<span data-ttu-id="e64c7-134">Codebeispiele zu Outlook-Add-Ins</span><span class="sxs-lookup"><span data-stu-id="e64c7-134">Outlook add-in code samples</span></span>](https://developer.microsoft.com/outlook/gallery/?filterBy=Outlook,Samples,Add-ins)
- [<span data-ttu-id="e64c7-135">Erste Schritte</span><span class="sxs-lookup"><span data-stu-id="e64c7-135">Get started</span></span>](https://docs.microsoft.com/outlook/add-ins/quick-start)