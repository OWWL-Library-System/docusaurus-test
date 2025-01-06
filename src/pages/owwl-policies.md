# OWWL Policy

Listing of policies and recommendations related to the shared catalog, patron database, and the circulation of OWWL Libraries' resources. These policies and recommendations have been set by the OWWL Advisory Committee, the Evergreen Advisory Committee, and the Director's Advisory Council.

## Administration
### Report processing schedule

EAC recommends following the [[ReportProcessingSchedule][ *report processing schedule* ]] and to take appropriate action as indicated on the schedule to maintain accurate patron and item records and to provide good customer service. (EAC, 4/2024; OWWLDAC, 5/2024)

### Shelving locations

Libraries should be consistent in the naming conventions they use for shelving locations. Shelving locations should use Title Case and should be of a reasonable length. Shelving locations should be added sparingly and should ideally correspond with an actual physical shelving location. (EAC 12/2023, OWWLDAC 02/2024)

### Circulation policy modifications

Requests for changes to a library's circulation policies in Evergreen should come from or CC the library's director. Library directors may appoint a designee for circulation policy updates; this designee may request circulation policy changes without CC'ing the library director. (EAC 10/2023; OWWLDAC 12/2023)

## Checkout
### Loan limits

Patrons are limited to 100 concurrent checkouts. (OWWLAC, 10/2013)
### Checkout blocks (overdue and fine threshold)

Patrons are blocked from checking out new materials if they have 5 or more overdue items and/or $5.00 or more in fines. (OWWLAC, 10/2013, 5/2016, 8/2018).

### Item availability for OWWL cardholders

Libraries should make items in their physical collection available to any OWWL cardholder in the same manner the items are available to the library's own cardholders. Libraries may restrict fragile, bulky, irreplaceable, or special circulation items from being put in transit and may require that such items be checked out and returned only at their owning library. (EAC 10/2023; OWWLDAC 12/2023)

## Loan Periods
### Loan periods follow the checkout library's circulation rules

To promote a consistent experience for patrons, items will circulate with due dates assigned following the checkout library's circulation rules, not the owning library's settings. In general, the system is configured to do this automatically.

(OWWLAC, 11/2013)
### Editing due dates when another library's item checks out with a "wrong" due date

In some instances, mis-configured or conflicting settings will cause the item to be circulated with a loan period that is <em>different </em>than the checkout library's policy for the given type of material. In this case, the checkout library may edit the due date so that it follows their normal loan period. (OWWLAC, 10/2013)

### Editing due dates when a patron needs extra time

In order to provide good customer service, library staff may edit the due date to provide extra time. The due date should not be extended beyond six weeks from the original due date without permission from the owning library. Do not use editing a due date to circumvent hold blocks, extend due dates on titles with holds, or prevent return of materials to the owning library. (OWWLAC, 3/2014; EAC 10/2022; PLSDAC 11/2022)
### Standard Loan Periods

OWWLAC recommendations for standard loan periods (OWWLAC, 11/8/2006, 4/25/2007, 11/2013), see: Evergreen.OwwlStandardLoanRules

## Renewals
### Renewal limits

The number of allowed renewals for a specific type of material is set by the CirculationModifier according to library policies and/or the Standard Loan policies. (11/2013)
### Renewal limit overrides

Avoid renewing items beyond the renewal limits. If the item belongs to another library, do not override the renewal limit without the permission of the owning library. (OWWLAC, 3/2014)
### Renewals blocked for items with holds

Items with holds - title, volume, or copy level - cannot be renewed. The item must be checked in and routed to the next pending hold. (OWWLAC, 2/22/2006, 11/2013)
### Renewals possible for accounts with circulation blocks

There are no renewal blocks based on circulation blocks - fines $5.00 and more, or 5 or more overdue items. Overdue items can be renewed to finalize bills and stop additional bills from accruing. (OWWLAC, 5/2016).

It is recommended practice that library staff renew any overdue items to finalize bills before accepting payment for overdue materials.

### Autorenewals

If a renewal is allowed, Evergreen should attempt an autorenewal. (EAC 10/2022; PLSDAC 11/2022)

## Bills
### Overdue Materials

Bills for *overdue materials* may be paid at any library and the bill payment kept by that library regardless of where the materials were checked out, where the materials were checked in, or who owns the materials. (11/2013)

### Lost Materials and Damaged Materials

Bills for *lost and damaged materials* may be paid at any library *but the payment must be forwarded to the owning library*.
   * Lost/damaged bills are paid using the Payment Type "Work" to clarify accounting at the payment library.
   * If being paid by check, the check must be addressed to the *library receiving payment* .
   * Checks and cash should not be sent via OWWL delivery and should be forwarded to the owning library using other means, such as by mail.
   * Payment for lost item processing fees should also be forwarded to the owning library. Forgiveness of lost item processing fees can be determined by the owning library.
   * Check with the owning library before telling a patron that you can accept a replacement copy in lieu of payment. Not all libraries accept replacement copies for lost or damaged items.

(11/2013; EAC 02/2022; PLSDAC 03/2022; PLSDAC 01/2023; EAC 03/2023; OWWLDAC 03/2023; EAC 06/2023; OWWLDAC 09/2023)

### Lost Materials Processing Fee bills

If a library charges processing fees in addition to lost materials bills, then the library should roll the fee into the item price or use the system-generated Lost Materials Processing Fee bill. No libraries should create manual bills, after the fact. Contact PLS to configure the system-generated processing fee bill.

(1/2014)
### "Credit"

Libraries should not convert excess payment into credit. (OWWLAC, 9/25/2012, 11/2013)
### "Forgive" payment type

When not holding a patron responsible for a fine, for whatever reason, use the "Forgive" PaymentType to clear the fine; add an annotation to attach relevant explanatory notes. (11/2013)

### Fine forgiveness

Libraries may choose to ignore and override overdue fines, accept payment for overdue fines, or forgive overdue fines according to their local policy. (OWWLDAC, 09/2024)

### Payment for items checked out policy

Libraries should not accept payment (whether actual payment or fine forgiveness) for bills on open circulations. (OWWLDAC, 09/2024)

### Amnesty Mode

Amnesty mode should not be used in place of going fine-free and should not be used unless in extenuating circumstances. (OWWLDAC, 09/2024)

## Patrons
### In-system vs. Out-of-system patrons

The OWWL Library System service area is defined as being formed by the counties of Wyoming, Livingston, Ontario, and Wayne in the state of New York.

In-system patrons are all full and part-time residents (whether permanently or temporarily, such as college students), as well as any person who attends school or pays property taxes, within the four county area or in a member library's chartered to serve area. This includes residents of "unserved" communities, or, those communities within the geographic boundary of the OWWL Library System, but outside of an OWWL Library System member library's chartered to serve area, subject to the Free Direct Access policy.

(OWWLAC, 5/22/2018; EAC 12/2021; PLSDAC 01/2022; EAC 08/2024; OWWLDAC 09/2024)

### Out-of-system Patron Statistical Categories

The Residency and School Code statistical categories include areas that are out side of, but border the four PLS counties and/or share school districts with PLS communities. For these areas and school districts, select the appropriate codes. For all patrons who live in non-contiguous areas, use the "OOS" code from the Residency and School District lists. This information is necessary to determine the use of library resources by neighboring communities for taxing and free direct access purposes. (OWWLAC, 5/22/2012, 2/2014, 5/2018; EAC 12/2021; PLSDAC 01/2022)

### Online Library Card Registration Policy

The [[%ATTACHURL%/Online Library Card Registration Policy - Adopted.pdf][Online Library Card Registration Policy - Adopted.pdf]] affirms that online library card registration is available to all full and part-time residents of Ontario, Wayne, Wyoming, and Livingston Counties as well as any person who attends school or pays property taxes in these counties. Out-of-system self-registration forms will not be processed. (EAC 10/2020; PLSDAC 11/2020)

### Standard patron registration form

A standard registration form is available to download from: Evergreen.PatronsRegistrationFormPrintable. Member libraries may use the form and customize it as necessary. (OWWLAC, 2/22/2006, 1/2014, 05/2018; EAC 12/2021; PLSDAC 01/2022)

### Registration paperwork retention

EAC recommends keeping registration paperwork for no longer than is reasonable for local workflow (i.e. time it takes to enter all data into the system) and recommends the proper disposal of registration paperwork, i.e. shredding.

If local library records retention policy indicates retaining paper forms for any length of time, they should be stored securely. Scanning and saving documents electronically is one method used by libraries for secure, long term storage. If libraries retain registration forms in any capacity, security of these forms is the responsibility of the library. (OWWLAC, 3/2005, 4/2005, 2/2014, 10/2014, 05/2018; EAC 12/2021; PLSDAC 01/2022)

### Driver's license in patron account

Driver's licenses are not to be added to patron records in Evergreen. There is no option to add driver's license number in a dedicated field, nor should this data be added in any other area in the patron record. (OWWLAC 10/2014, PLS Policy 1/2015)

Libraries may include driver's license numbers in their paper registration files, security of these files is the responsibility of the library.

### Updates to patron accounts

Changing home library, address, library card number, etc. does not necessitate completely new registration. If a patron’s home library or address has changed, the updating library should change the residency code, school code, home library, and hold pickup library as necessary. (OWWLAC, 2/2014; EAC 12/2021; PLSDAC 01/2022)

### Patron has a name change

Changes to a patron’s legal name or preferred name can be made based on local library policy. (OWWLAC, 2/2014; EAC 12/2021; PLSDAC 01/2022)

### Agency cards

Cards may be issued to specific types of agencies for use by authorized agency staff persons, according to the guidelines laid out in the Evergreen.PatronsAgencyUserRecords page and agreement. Classroom teachers should be referred to their school librarian/BOCES for group loans. (Unknown origin; updated EAC 06/2023; OWWLDAC 09/2023)

### Account expiration

Patron accounts will expire every two years; staff must verify and update contact information before extending another two years. (OWWLAC, 10/2004, 1/2014)

Patrons with email accounts will receive a pre-expiration email notice, alerting them to contact the library to extend their library privileges. (OWWLAC, 1/2014)

### Expired accounts marked inactive

Patron accounts that have been Expired for more than 3 years will be marked "Inactive" automatically by the system. The accounts will be flagged with an Alert stating the reason for being marked inactive, and remain in the database should the patrons return to the library. (OWWLAC, 2/2014)

### Deleting expired accounts

Patron records that have been expired for 6 years will be deleted, including outstanding bills. (OWWLAC, 9/2014; EAC 12/2021; PLSDAC 01/2022)

### Accessing !OWWL2Go

Only patrons with active, unexpired accounts can access !OWWL2go materials. (OWWLAC, 2/26/2013, 2/2014; EAC 12/2021; PLSDAC 01/2022)

### Renew patron account privilege

Patron accounts may be renewed in person, over the phone, or by email as per the individual library's local policy (OWWLAC, 1/22/2013; 1/2014; EAC 12/2021; PLSDAC 01/2022)

## Items
### Mark Lost Manually

Any library can mark an item lost, even items not owned by that library. Marking an item lost will create a Lost Materials bill on the patron's account, which will typically block the patron from further circulation. Generally, it is recommended that if there is any doubt whether the item is actually lost, libraries should renew the item (within remaining renewal limits and respecting hold blocks) and allow the item to become overdue until lost. (OWWLAC, 4/2014; EAC 04/2022; PLSDAC 05/2022)
### Mark Item Lost by Patron, item not owned by your library

Any library may manually mark lost any other library's materials. When in doubt, contact the owning library before taking action. (OWWLAC, 4/2014)
### Overdue Until Lost

All items that are overdue more than 8 weeks will be marked as lost, automatically by the Evergreen system. This will create a Lost Materials bill on the patron's account, which will typically block the patron from further circulation. (OWWLAC, 4/2014)
### Items Damaged "Beyond Repair"

If an item is damaged to an extent that it *cannot be repaired* and remains checked out to the responsible patron, the item should be [[Evergreen.MarkItemDamaged22][Marked Damaged]] and the patron billed for the full replacement price. (OWWLAC, 4/2014)
### Damaged Items Not Owned by your Library

If a damaged item is not owned by your library, use a [[Evergreen.HoldsRequestItems][Recall Hold]] to send the item back to the owning library for evaluation and to be marked damaged as necessary. (OWWLAC, 4/2014; EAC 04/2022; PLSDAC 05/2022)
### Payments accepted for lost/damaged items owned by another library

Any library may accept payment for any other libraries' lost or damaged materials, *but the payment must be forwarded to the owning library.* For more information, see the procedure under [[Evergreen.OwwlPolicy#Lost_Materials_and_Damaged_Materials][Lost Materials and Damaged Materials]]. (OWWLAC, 4/2014; EAC 04/2022; PLSDAC 05/2022)

### Deletion of items

Items with particular statuses will be deleted from Evergreen by System staff on the following schedule:
   * Missing items three years after last status update
   * Lost and paid items six months after last status update
   * Lost items when patron is deleted
Libraries are encouraged to delete items sooner according to local policy. (OWWLDAC, 09/2024)

## Holds
### Hold Limits

Patrons may place up to 20 active holds. Patrons may place up to 30 additional suspended holds. This policy is set in system configuration. (OWWLAC, 3/2014; EAC 04/2022; PLSDAC 05/2022)
### Holds not picked up

All holds not picked up in a reasonable amount of time, not to exceed 7-10 days, as defined by local policy, should be removed from the holds shelf, the patron hold cancelled, and the item routed to fill other holds or back to the owning library for reshelving. (OWWLAC, 4/2014; EAC 04/2022; PLSDAC 05/2022)

### Holds and accounts with circulation blocks

If a patron's account has circulation blocks - fines of $5.00 or more or more than 5 overdue items - they may still place holds, and the holds will be captured and sent to the patron's pickup library as normal. However, the patron must resolve the circulation blocks before they will be able to check out their hold items. (OWWLAC, 8/2018; EAC 04/2022; PLSDAC 05/2022)

### Age Based Hold Protection

Age-based hold protection limits holds to those requests being picked up at the owning library, for a period of two months based on the copy create date. Use of age-based hold protection is optional, can be applied to all types of new materials, and can be removed from a copy at any time, as determined by the owning library. (OWWLAC, 2/26/2013, 4/2014)

## Cataloging
### Older titles

PLS reserves the right to refuse new title record requests for older titles.

Libraries should carefully review materials prior to request to ensure that they are still accurate, relevant, and appropriate for the collection. Full details and selection criteria can be found here: Evergreen.CollectionDevelopmentOlderTitleGuidelines

(OWWLAC, 4/2014)
### VHS

PLS does not accept requests to create new title records for VHS materials (with the exception of local history materials). (OWWLAC, 4/2014; EAC 06/2022)

### Close enough records

PLS Cataloging will combine in the same title record multiple editions when the essential work is the same, but the specific copy varies in minor details. For example: hard cover and trade paperback editions of the same title, books with included discussion guide materials, differing publishers or distributors, etc. (OWWLAC 5/22/2012, 4/2014)

For full guidelines regarding combined editions sharing a single title record, see: Evergreen.CatalogCloseEnoughRecords
### Multiple format combinations

PLS Cataloging will combine formats in a single title record when the combined formats are essential to the use of the material. For example: books with accompanying computer discs. (OWWLAC, 4/2014)

## Grievances

If OWWL policies are abused, all library staff and directors should follow the EAC Grievance Policy and Procedure.

See: Members.OwwlacGrievancePolicy
