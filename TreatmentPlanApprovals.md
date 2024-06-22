# Data Dictionary for Collection: TreatmentPlanApprovals
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| OfficeId | str | |
| ConsentInfo | str | |
| TreatmentPlanId | str | |
| DateSigned | str | |
| PatientId | str | |
| Signature | str | |
| Phases | list | |
| SignedDateTime | DatetimeWithNanoseconds | |
| document_id | str | |

## Example Document
```json
{'OfficeId': '17003007', 'ConsentInfo': {'Consents': [{'Codes': ['all'], 'ButtonLink': '', 'Text': '<p><b>Examination &amp; X-Rays</b> <br>I understand that the initial visit may require radiographs to complete the examination, diagnosis, and treatment plan.<br><br><b>Drugs, Medication, &amp; Sedation</b><br>I have been informed and understand that   antibiotics, analgesics, and other medications can cause allergic reactions causing redness, swelling of tissue, pain, itching, vomiting, and/or anaphylactic shock (severe allergic reaction). They may cause drowsiness and a lack of awareness and   coordination, which can be increased by the use of alcohol or other drugs. I understand and fully agree not to operate any vehicle or hazardous device for at least 12 hours or until fully recovered from the effects of the anesthetic medication and   drugs that may have been given me in the office for my treatment. I understand that failure to take medications prescribed for me in the manner prescribed may offer risks of continued or aggravated infection, pain, and potential resistance to   effective treatment of my condition. I understand that antibiotics can reduce the effectiveness of oral contraceptives.<br><br><b>Changes in Treatment Plan</b><br>I understand that during treatment, it may be necessary to change or add procedures   because of conditions found while working on teeth that were not discovered during an examination, the most common being root canal therapy following routine restorative procedures. I give my permission to the Dentist to make any or all changes and   additions as necessary.<br><br><b>Temporomandibular Joint Dysfunctions (TMJ)</b><br>I understand that symptoms of popping, clicking, locking and pain can intensify or develop in the joints of the lower jaw (near the ear) after routine dental   treatment wherein the mouth is held in the open position. However, symptoms of TMJ associated with dental treatment are usually transitory and well tolerated by most patients. I understand that should the need for treatment arise, then I will be   referred to a specialist for treatment, and the cost of which is my responsibility.<br><br><b>Fillings</b><br>I understand that care must be exercised in chewing on filling during the first 24 hours to avoid breakage, and tooth sensitivity is a   common after-effect of a newly placed filling.<br><br><b>Removal of Teeth (Extraction)</b><br>I understand removing teeth does not always remove all infection present and it may be necessary to have further treatment. I understand the risks   involved in having teeth removed, some of which are pain, swelling, spread of infection, dry socket, loss of feeling in my teeth, lips, tongue, and surrounding tissue (paresthesia) that can last for an indefinite period or a fractured jaw. I   understand I may need further treatment by a specialist or even hospitalization if complications arise during or following treatment, the cost of which is my responsibility.<br><br><b>Crowns, Bridges, Veneers, &amp; Bonding</b><br>I understand that   sometimes it is not possible to match the color of natural teeth exactly with artificial teeth. I further understand that I may be wearing temporary crowns, which may come off easily and that I must be careful to ensure that they are kept on until   the permanent crowns are delivered. I realize that the final opportunity to make changes in my new crowns, bridge or cap (including shape, fit, size, placement, and color) will be done before cementation. It has been explained to me that, in very   few cases, cosmetic procedures may result in the need for future root canal treatment, which cannot always be predicted or anticipated. I understand that cosmetic procedures may affect tooth surfaces and may require modification of daily cleaning   procedures.<br><br><b>Dentures - Complete or Partial</b><br>I realize that full or partial dentures are artificial, constructed of plastic, metal and/or porcelain. The problems of wearing those appliances have been explained to me including   looseness, soreness, and possible breakage. I realize the final opportunity to make changes in my new denture (including shape, fit, size, placement, and color) will be a "teeth in wax" try-in visit. I understand that most dentures require relining   approximately three to twelve months after initial placement. The cost of this procedure is not the initial denture fee.<br><br><b>Endontontic Treatment (Root Canal)</b><br>I realize there is no guarantee that root canal treatment will save my   tooth and complications can occur from the treatment and that occasionally metal objects are cemented in the tooth, or extend through the root, which does not necessarily affect the success of the treatment. I understand that occasionally   additional surgical procedures may be necessary following root canal treatment (apicoectomy).<br><br><b>Periodontal Treatment</b> <br>I understand that I have a serious condition causing gum inflammation and/or bone loss and that it can lead to the   loss of my teeth. Alternative treatment plans have been explained to me, including non-surgical cleaning, gum surgery and/or extractions. I understand the success of treatment depends in part on my efforts to brush and floss daily, receive regular   cleaning as directed, following a healthy diet, avoid tobacco products and follow other recommendations.<br><br></p>   <p><strong>By Signing I Acknowledge the Following: </strong></p>   <ul>     <li style="padding - bottom: 15px; ">I understand that every reasonable effort will be made to ensure that my condition is treated properly, although it\'s not possible to guarantee perfect results. By signing below, I acknowledge that I have received adequate information about the       proposed treatment, that I understand this information and that all of my questions have been answered to my satisfaction.</li>     <li style="padding - bottom: 15px; ">I have had the opportunity to discuss any alternatives to this treatment with my dentist. All of my questions were answered to my satisfaction regarding such alternatives and their risks, benefits, and costs.</li>     <li style="padding - bottom: 15px; ">No guarantee or assurance has been given to me by anyone that the proposed treatment or surgery will cure or improve the condition(s) listed above.</li>   </ul>', 'Name': 'Consent', 'Id': 1}], 'Office': '17003007'}, 'TreatmentPlanId': '58', 'DateSigned': '01/04/2023 3:32pm', 'PatientId': '31', 'Signature': 'data:image/png;base64,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', 'Phases': ['0'], 'SignedDateTime': DatetimeWithNanoseconds(2023, 1, 4, 23, 32, 37, 791000, tzinfo=datetime.timezone.utc), 'document_id': '0wz2UKd0Jk27y9PCcvgd'}
```