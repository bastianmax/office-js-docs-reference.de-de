
# <a name="context"></a><span data-ttu-id="f87c1-101">context</span><span class="sxs-lookup"><span data-stu-id="f87c1-101">context</span></span>

### <a name="officeofficemdcontext"></a><span data-ttu-id="f87c1-102">[Office](Office.md).context</span><span class="sxs-lookup"><span data-stu-id="f87c1-102">[Office](Office.md).context</span></span>

<span data-ttu-id="f87c1-p101">Der Office.context-Namespace stellt gemeinsam genutzte Oberflächen bereit, die von Add-Ins in allen Office-Apps verwendet werden. Diese Auflistung dokumentiert nur die Schnittstellen, die von Outlook-Add-Ins verwendet werden. Eine vollständige Auflistung des Office.context-Namespaces finden Sie in der [Office.context-Referenz in der freigegebenen API](/javascript/api/office/office.context).</span><span class="sxs-lookup"><span data-stu-id="f87c1-p101">The Office.context namespace provides shared interfaces that are used by add-ins in all of the Office apps. This listing documents only those interfaces that are used by Outlook add-ins. For a full listing of the Office.context namespace, see the [Office.context reference in the Shared API](/javascript/api/office/office.context).</span></span>

##### <a name="requirements"></a><span data-ttu-id="f87c1-105">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="f87c1-105">Requirements</span></span>

|<span data-ttu-id="f87c1-106">Anforderung</span><span class="sxs-lookup"><span data-stu-id="f87c1-106">Requirement</span></span>| <span data-ttu-id="f87c1-107">Wert</span><span class="sxs-lookup"><span data-stu-id="f87c1-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="f87c1-108">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="f87c1-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="f87c1-109">1.0</span><span class="sxs-lookup"><span data-stu-id="f87c1-109">1.0</span></span>|
|[<span data-ttu-id="f87c1-110">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="f87c1-110">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="f87c1-111">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="f87c1-111">Compose or read</span></span>|

### <a name="namespaces"></a><span data-ttu-id="f87c1-112">Namespaces</span><span class="sxs-lookup"><span data-stu-id="f87c1-112">Namespaces</span></span>

<span data-ttu-id="f87c1-113">[Mailbox](office.context.mailbox.md): ermöglicht den Zugriff auf das Objektmodell von Outlook-add-in für Microsoft Outlook und Microsoft Outlook im Web.</span><span class="sxs-lookup"><span data-stu-id="f87c1-113">[mailbox](office.context.mailbox.md): Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

### <a name="members"></a><span data-ttu-id="f87c1-114">Elemente</span><span class="sxs-lookup"><span data-stu-id="f87c1-114">Members</span></span>

####  <a name="displaylanguage-string"></a><span data-ttu-id="f87c1-115">displayLanguage :String</span><span class="sxs-lookup"><span data-stu-id="f87c1-115">displayLanguage :String</span></span>

<span data-ttu-id="f87c1-116">Ruft das vom Benutzer im Sprachtagformat RFC 1766 angegebene Gebietsschema (Sprache) für die Benutzeroberfläche der Office-Hostanwendung ab.</span><span class="sxs-lookup"><span data-stu-id="f87c1-116">Gets the locale (language) in RFC 1766 Language tag format specified by the user for the UI of the Office host application.</span></span>

<span data-ttu-id="f87c1-117">Der `displayLanguage`-Wert gibt die aktuelle Einstellung **Anzeigesprache** wieder, die mit **Datei > Optionen > Sprache** in der Office-Hostanwendung angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="f87c1-117">The `displayLanguage` value reflects the current **Display Language** setting specified with **File > Options > Language** in the Office host application.</span></span>

##### <a name="type"></a><span data-ttu-id="f87c1-118">Typ:</span><span class="sxs-lookup"><span data-stu-id="f87c1-118">Type:</span></span>

*   <span data-ttu-id="f87c1-119">String</span><span class="sxs-lookup"><span data-stu-id="f87c1-119">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="f87c1-120">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="f87c1-120">Requirements</span></span>

|<span data-ttu-id="f87c1-121">Anforderung</span><span class="sxs-lookup"><span data-stu-id="f87c1-121">Requirement</span></span>| <span data-ttu-id="f87c1-122">Wert</span><span class="sxs-lookup"><span data-stu-id="f87c1-122">Value</span></span>|
|---|---|
|[<span data-ttu-id="f87c1-123">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="f87c1-123">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="f87c1-124">1.0</span><span class="sxs-lookup"><span data-stu-id="f87c1-124">1.0</span></span>|
|[<span data-ttu-id="f87c1-125">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="f87c1-125">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="f87c1-126">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="f87c1-126">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="f87c1-127">Beispiel</span><span class="sxs-lookup"><span data-stu-id="f87c1-127">Example</span></span>

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

####  <a name="officetheme-object"></a><span data-ttu-id="f87c1-128">officeTheme :Object</span><span class="sxs-lookup"><span data-stu-id="f87c1-128">officeTheme :Object</span></span>

<span data-ttu-id="f87c1-129">Bietet Zugriff auf die Eigenschaften für Office-Farbdesigns.</span><span class="sxs-lookup"><span data-stu-id="f87c1-129">Provides access to the properties for Office theme colors.</span></span>

> [!NOTE]
> <span data-ttu-id="f87c1-130">Dieser Member wird in Outlook für iOS oder Outlook für Android nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="f87c1-130">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="f87c1-p102">Mit Office-Farbdesigns können Sie das Farbschema Ihres Add-Ins mit dem aktuellen Office-Design, das vom Benutzer mit **Datei > Office-Konto > Office-Design-UI** ausgewählt wurde, koordinieren. Das Farbschema wird auf alle Office-Hostanwendungen angewendet. Das Verwenden von Office-Designfarben eignet sich für E-Mail- und Aufgabenbereichs-Add-Ins.</span><span class="sxs-lookup"><span data-stu-id="f87c1-p102">Using Office theme colors let's you coordinate the color scheme of your add-in with the current Office theme selected by the user with **File > Office Account > Office Theme UI**, which is applied across all Office host applications. Using Office theme colors is appropriate for mail and task pane add-ins.</span></span>

##### <a name="type"></a><span data-ttu-id="f87c1-133">Typ:</span><span class="sxs-lookup"><span data-stu-id="f87c1-133">Type:</span></span>

*   <span data-ttu-id="f87c1-134">Object</span><span class="sxs-lookup"><span data-stu-id="f87c1-134">Object</span></span>

##### <a name="properties"></a><span data-ttu-id="f87c1-135">Eigenschaften:</span><span class="sxs-lookup"><span data-stu-id="f87c1-135">Properties:</span></span>

|<span data-ttu-id="f87c1-136">Name</span><span class="sxs-lookup"><span data-stu-id="f87c1-136">Name</span></span>| <span data-ttu-id="f87c1-137">Typ</span><span class="sxs-lookup"><span data-stu-id="f87c1-137">Type</span></span>| <span data-ttu-id="f87c1-138">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="f87c1-138">Description</span></span>|
|---|---|---|
|`bodyBackgroundColor`| <span data-ttu-id="f87c1-139">Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="f87c1-139">String</span></span>|<span data-ttu-id="f87c1-140">Ruft die Hintergrundfarbe des Office-Designkörpers als hexadezimales Farbtriplet ab.</span><span class="sxs-lookup"><span data-stu-id="f87c1-140">Gets the Office theme body background color as a hexadecimal color triplet.</span></span>|
|`bodyForegroundColor`| <span data-ttu-id="f87c1-141">Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="f87c1-141">String</span></span>|<span data-ttu-id="f87c1-142">Ruft die Vordergrundfarbe des Office-Designkörpers als hexadezimales Farbtriplet ab.</span><span class="sxs-lookup"><span data-stu-id="f87c1-142">Gets the Office theme body foreground color as a hexadecimal color triplet.</span></span>|
|`controlBackgroundColor`| <span data-ttu-id="f87c1-143">Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="f87c1-143">String</span></span>|<span data-ttu-id="f87c1-144">Ruft die Hintergrundfarbe des Office-Designsteuerelements als hexadezimales Farbtriplet ab.</span><span class="sxs-lookup"><span data-stu-id="f87c1-144">Gets the Office theme control background color as a hexadecimal color triplet.</span></span>|
|`controlForegroundColor`| <span data-ttu-id="f87c1-145">Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="f87c1-145">String</span></span>|<span data-ttu-id="f87c1-146">Ruft die Vordergrundfarbe des Office-Designsteuerelements als hexadezimales Farbtriplet ab.</span><span class="sxs-lookup"><span data-stu-id="f87c1-146">Gets the Office theme body control color as a hexadecimal color triplet.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="f87c1-147">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="f87c1-147">Requirements</span></span>

|<span data-ttu-id="f87c1-148">Anforderung</span><span class="sxs-lookup"><span data-stu-id="f87c1-148">Requirement</span></span>| <span data-ttu-id="f87c1-149">Wert</span><span class="sxs-lookup"><span data-stu-id="f87c1-149">Value</span></span>|
|---|---|
|[<span data-ttu-id="f87c1-150">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="f87c1-150">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="f87c1-151">1.3</span><span class="sxs-lookup"><span data-stu-id="f87c1-151">1.3</span></span>|
|[<span data-ttu-id="f87c1-152">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="f87c1-152">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="f87c1-153">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="f87c1-153">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="f87c1-154">Beispiel</span><span class="sxs-lookup"><span data-stu-id="f87c1-154">Example</span></span>

```js
function applyOfficeTheme(){
  // Get office theme colors.
  var bodyBackgroundColor = Office.context.officeTheme.bodyBackgroundColor;
  var bodyForegroundColor = Office.context.officeTheme.bodyForegroundColor;
  var controlBackgroundColor = Office.context.officeTheme.controlBackgroundColor
  var controlForegroundColor = Office.context.officeTheme.controlForegroundColor;

  // Apply body background color to a CSS class.
  $('.body').css('background-color', bodyBackgroundColor);
}
```

####  <a name="roamingsettings-roamingsettingsjavascriptapioutlook14officeroamingsettings"></a><span data-ttu-id="f87c1-155">roamingSettings :[RoamingSettings](/javascript/api/outlook_1_4/office.RoamingSettings)</span><span class="sxs-lookup"><span data-stu-id="f87c1-155">roamingSettings :[RoamingSettings](/javascript/api/outlook_1_4/office.RoamingSettings)</span></span>

<span data-ttu-id="f87c1-156">Ruft ein Objekt ab, das die benutzerdefinierten Einstellungen oder den Status eines Mail-Add-Ins im Postfach eines Benutzers darstellt.</span><span class="sxs-lookup"><span data-stu-id="f87c1-156">Gets an object that represents the custom settings or state of a mail add-in saved to a user's mailbox.</span></span>

<span data-ttu-id="f87c1-157">Mit dem `RoamingSettings`-Objekt können Sie Daten für ein Mail-Add-In speichern und darauf zugreifen, die im Postfach eines Benutzers gespeichert sind, damit diese Daten für das Add-In verfügbar sind, wenn es über eine beliebige Hostclientanwendung zum Zugreifen auf das Postfach ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="f87c1-157">The `RoamingSettings` object lets you store and access data for a mail add-in that is stored in a user's mailbox, so that is available to that add-in when it is running from any host client application used to access that mailbox.</span></span>

##### <a name="type"></a><span data-ttu-id="f87c1-158">Typ:</span><span class="sxs-lookup"><span data-stu-id="f87c1-158">Type:</span></span>

*   [<span data-ttu-id="f87c1-159">RoamingSettings</span><span class="sxs-lookup"><span data-stu-id="f87c1-159">RoamingSettings</span></span>](/javascript/api/outlook_1_4/office.RoamingSettings)

##### <a name="requirements"></a><span data-ttu-id="f87c1-160">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="f87c1-160">Requirements</span></span>

|<span data-ttu-id="f87c1-161">Anforderung</span><span class="sxs-lookup"><span data-stu-id="f87c1-161">Requirement</span></span>| <span data-ttu-id="f87c1-162">Wert</span><span class="sxs-lookup"><span data-stu-id="f87c1-162">Value</span></span>|
|---|---|
|[<span data-ttu-id="f87c1-163">Mindestversion des Postfachanforderungssatzes</span><span class="sxs-lookup"><span data-stu-id="f87c1-163">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="f87c1-164">1.0</span><span class="sxs-lookup"><span data-stu-id="f87c1-164">1.0</span></span>|
|[<span data-ttu-id="f87c1-165">Mindestberechtigungsstufe</span><span class="sxs-lookup"><span data-stu-id="f87c1-165">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="f87c1-166">Eingeschränkt</span><span class="sxs-lookup"><span data-stu-id="f87c1-166">Restricted</span></span>|
|[<span data-ttu-id="f87c1-167">Zutreffender Outlook-Modus</span><span class="sxs-lookup"><span data-stu-id="f87c1-167">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="f87c1-168">Verfassen oder Lesen</span><span class="sxs-lookup"><span data-stu-id="f87c1-168">Compose or read</span></span>|