
# <a name="context"></a><span data-ttu-id="6661f-101">context</span><span class="sxs-lookup"><span data-stu-id="6661f-101">context</span></span>

### <span data-ttu-id="6661f-p101">[Office](Office.md).context</span><span class="sxs-lookup"><span data-stu-id="6661f-p101">[Office](Office.md). context</span></span>

<span data-ttu-id="6661f-p102">Der Office.context-Namespace stellt gemeinsam genutzte Oberflächen bereit, die von Add-Ins in allen Office-Apps verwendet werden. Diese Auflistung dokumentiert nur die Schnittstellen, die von Outlook-Add-Ins verwendet werden. Eine vollständige Auflistung des Office.context-Namespaces finden Sie in der [Office.context-Referenz in der freigegebenen API](/javascript/api/office/office.context).</span><span class="sxs-lookup"><span data-stu-id="6661f-p102">The Office.context namespace provides shared interfaces that are used by add-ins in all of the Office apps. This listing documents only those interfaces that are used by Outlook add-ins. For a full listing of the Office.context namespace, see the [Office.context reference in the Shared API](/javascript/api/office/office.context).</span></span>


##### <a name="requirements"></a><span data-ttu-id="6661f-106">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="6661f-106">Requirements</span></span>

|<span data-ttu-id="6661f-107">Anforderung</span><span class="sxs-lookup"><span data-stu-id="6661f-107">Requirement</span></span>| <span data-ttu-id="6661f-108">Wert</span><span class="sxs-lookup"><span data-stu-id="6661f-108">Value</span></span>|
|---|---|
|[<span data-ttu-id="6661f-109">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="6661f-109">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="6661f-110">1.0</span><span class="sxs-lookup"><span data-stu-id="6661f-110">1.0</span></span>|
|[<span data-ttu-id="6661f-111">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="6661f-111">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="6661f-112">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="6661f-112">Compose or read</span></span>|

### <a name="namespaces"></a><span data-ttu-id="6661f-113">Namespaces</span><span class="sxs-lookup"><span data-stu-id="6661f-113">Namespaces</span></span>

<span data-ttu-id="6661f-114">[Postfach](office.context.mailbox.md) – ermöglicht den Zugriff auf das Objektmodell von Outlook-add-in für Microsoft Outlook und Microsoft Outlook im Web.</span><span class="sxs-lookup"><span data-stu-id="6661f-114">[mailbox](office.context.mailbox.md) - Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

### <a name="members"></a><span data-ttu-id="6661f-115">Elemente</span><span class="sxs-lookup"><span data-stu-id="6661f-115">Members</span></span>

####  <a name="displaylanguage-string"></a><span data-ttu-id="6661f-116">displayLanguage :String</span><span class="sxs-lookup"><span data-stu-id="6661f-116">displayLanguage :String</span></span>

<span data-ttu-id="6661f-117">Ruft das vom Benutzer im Sprachtagformat RFC 1766 angegebene Gebietsschema (Sprache) für die Benutzeroberfläche der Office-Hostanwendung ab.</span><span class="sxs-lookup"><span data-stu-id="6661f-117">Gets the locale (language) in RFC 1766 Language tag format specified by the user for the UI of the Office host application.</span></span>

<span data-ttu-id="6661f-118">Der `displayLanguage`-Wert gibt die aktuelle Einstellung **Anzeigesprache** wieder, die mit **Datei > Optionen > Sprache** in der Office-Hostanwendung angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="6661f-118">The `displayLanguage` value reflects the current **Display Language** setting specified with **File > Options > Language** in the Office host application.</span></span>

##### <a name="type"></a><span data-ttu-id="6661f-119">Typ:</span><span class="sxs-lookup"><span data-stu-id="6661f-119">Type:</span></span>

*   <span data-ttu-id="6661f-120">String</span><span class="sxs-lookup"><span data-stu-id="6661f-120">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="6661f-121">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="6661f-121">Requirements</span></span>

|<span data-ttu-id="6661f-122">Anforderung</span><span class="sxs-lookup"><span data-stu-id="6661f-122">Requirement</span></span>| <span data-ttu-id="6661f-123">Wert</span><span class="sxs-lookup"><span data-stu-id="6661f-123">Value</span></span>|
|---|---|
|[<span data-ttu-id="6661f-124">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="6661f-124">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="6661f-125">1.0</span><span class="sxs-lookup"><span data-stu-id="6661f-125">1.0</span></span>|
|[<span data-ttu-id="6661f-126">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="6661f-126">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="6661f-127">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="6661f-127">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="6661f-128">Beispiel</span><span class="sxs-lookup"><span data-stu-id="6661f-128">Example</span></span>

```js
function sayHelloWithDisplayLanguage() {
  var myDisplayLanguage = Office.context.displayLanguage;
  switch (myDisplayLanguage) {
    case 'en-US':
      write('Hello!');
      break;
    case 'en-NZ':
      write('G\'day mate!');
      break;
  }
}
// Function that writes to a div with id='message' on the page.
function write(message){
  document.getElementById('message').innerText += message;
}
```

####  <a name="roamingsettings-roamingsettingsjavascriptapioutlook12officeroamingsettings"></a><span data-ttu-id="6661f-129">roamingSettings :[RoamingSettings](/javascript/api/outlook_1_2/office.RoamingSettings)</span><span class="sxs-lookup"><span data-stu-id="6661f-129">roamingSettings :[RoamingSettings](/javascript/api/outlook_1_2/office.RoamingSettings)</span></span>

<span data-ttu-id="6661f-130">Ruft ein Objekt ab, das die benutzerdefinierten Einstellungen oder den Status eines Mail-Add-Ins im Postfach eines Benutzers darstellt.</span><span class="sxs-lookup"><span data-stu-id="6661f-130">Gets an object that represents the custom settings or state of a mail add-in saved to a user's mailbox.</span></span>

<span data-ttu-id="6661f-131">Mit dem `RoamingSettings`-Objekt können Sie Daten für ein Mail-Add-In speichern und darauf zugreifen, die im Postfach eines Benutzers gespeichert sind, damit diese Daten für das Add-In verfügbar sind, wenn es über eine beliebige Hostclientanwendung zum Zugreifen auf das Postfach ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6661f-131">The `RoamingSettings` object lets you store and access data for a mail add-in that is stored in a user's mailbox, so that is available to that add-in when it is running from any host client application used to access that mailbox.</span></span>

##### <a name="type"></a><span data-ttu-id="6661f-132">Typ:</span><span class="sxs-lookup"><span data-stu-id="6661f-132">Type:</span></span>

*   [<span data-ttu-id="6661f-133">RoamingSettings</span><span class="sxs-lookup"><span data-stu-id="6661f-133">RoamingSettings</span></span>](/javascript/api/outlook_1_2/office.RoamingSettings)

##### <a name="requirements"></a><span data-ttu-id="6661f-134">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="6661f-134">Requirements</span></span>

|<span data-ttu-id="6661f-135">Anforderung</span><span class="sxs-lookup"><span data-stu-id="6661f-135">Requirement</span></span>| <span data-ttu-id="6661f-136">Wert</span><span class="sxs-lookup"><span data-stu-id="6661f-136">Value</span></span>|
|---|---|
|[<span data-ttu-id="6661f-137">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="6661f-137">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="6661f-138">1.0</span><span class="sxs-lookup"><span data-stu-id="6661f-138">1.0</span></span>|
|[<span data-ttu-id="6661f-139">Mindestberechtigungsstufe</span><span class="sxs-lookup"><span data-stu-id="6661f-139">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="6661f-140">Eingeschränkt</span><span class="sxs-lookup"><span data-stu-id="6661f-140">Restricted</span></span>|
|[<span data-ttu-id="6661f-141">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="6661f-141">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="6661f-142">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="6661f-142">Compose or read</span></span>|