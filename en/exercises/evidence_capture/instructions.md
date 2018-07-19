
**The Chain of Custody: How to handle forensic data**

The Chain of Custody (often referred to as audit trail or chain of evidence) is the process of preserving the integrity of the digital evidence. Being able to maintain the Chain of Custody is very important for forensic evidence. This means that you need to record, and be able to prove, that authorized personnel were in control of the evidence at all times, and that no unauthorized person or device or mechanism could have altered the evidence while in our custody.

To maintain the Chain of Custody, it is imperative to carefully document what happens to the evidence. This means:

- **Store the evidence in an anti-static bag**, or similar appropriate container that will protect the device from static electricity or other destructive forces.

- **Clearly label the evidence.** There must be no confusion about a piece of evidence. All evidence, whether hard drives, USB sticks, DVDs, etc. should be clearly labeled with the following information:

  - What the evidence relates to
  - Who received the evidence
  - Location of where the evidence was received
  - Location of where the evidence was sourced from
  - The date and time the evidence came into our possession
  - Any other notes you think are relevant regarding this piece of evidence (the specifications of the computer a hard drive came from, etc.)

- Every time the evidence changes hands, **the next person responsible for the evidence should "sign for it"**, which means documentation should be produced where the recipient of the evidence confirms they have received the evidence into their custody with their signature.

- **Deny unauthorized personnel from accessing the data** - Every reasonable effort must be taken to prevent unauthorized access to the stored evidence. This means:
  - Storing the evidence in a locked safe
  - Controlling access to areas where the evidence is stored and analyzed
  - Not leaving unauthorized people alone with the evidence

- **If you have to send evidence via courier, or the postal service**:

  - Special containers should be used to seal the evidence in such a way that the container cannot be opened without it being apparent (e.g. seal with special tape that, if removed, cannot be replaced without showing that the container has been opened).
  - Make a copy (image) of the evidence before sending the original through the post or courier service, and generate a hash of the image.


**Live or Dead Imaging?**

Different processes and tools are used depending on what kind of data acquisition and investigation will be done. However, in order to make a correct decision on how to get the forensic image, you should take into account the following questions:

- Is the computer networked? The data in a networked device could be remotely erased. That's why this question is relevant and time sensitive.
- Is the computer running? Important volatile information could be lost if the computer is turned off.
- Do you want to preserve volatile data? Nowadays, sophisticated malware hides on volatile data and modern web browsers can operate in ‘incognito’ or ‘private’ mode (no information is saved). In most of these cases, preserving live evidence is the only way to go, so deleting it may cause loss of evidence. Therefore this decision should be taken in advance, based on the details gathered before the data acquisition.
- Is full-disk encryption enabled? An encrypted disk could complicate the investigation. If the disk is encrypted, the investigator should ask for the password and decrypt the disk manually.
- Is the console unlocked? if the console is locked, a live CD should be used.

Regarding the definitions, we call 'dead imaging', or 'offline imaging', the process of obtaining evidence from systems that are switched off and where no data processing is taking place, while 'live imaging', or 'memory imaging', refers to the process of making a bit-by-bit copy of memory in order to preserve the volatile data available in the device. There is a lot of information of evidentiary value that could be found in a live system. Switching it off may cause loss of volatile data such as running processes, network connections and mounted file systems. On the other hand, leaving a computer running may cause evidence to be altered or deleted. Therefore the investigator needs to decide what alternative is best in each given situation. Another approach is to use specialized tools to extract volatile data from the computer before shutting it down.


___

##### Variant: Live imaging tools and procedures

!INCLUDE "variant_live_capture.md"

___

##### Variant: Offline / Dead imaging tools and procedures

!INCLUDE "variant_offline_capture.md"
