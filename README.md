# 5G-Subscriber-Identifier


Identifiers are used who uniquely recognize the entity. Send all the connection characteristics are tide to this identity. For example the device identity can be used it will be fine if it is a blacklisted device or not. Subscription identity is used to define if the subscription allows a certain 5G service or not. There are two different identities in 5G system as follows

i) Device Identity

ii) Subscription Identity

Subscription Identifier
i) SUPI (Subecription Permanent Identity) or IMSI

It can take two format 
   a) IMSI
   b) NAI

If an operator have 5G system, it will use IMSI. Suppose in some case they have Wi-Fi or non-3GPP for supporting 5G connectivity then they will use an NAI. IMSI it has 15 or 16 digits it has three components such as MCC, MNC, MSIN. Mobile country code(MCC) used to know the country, Mobile Network Code(MNC) to know which operator of that country, Mobile Subscriber Identification Number(MSIN) to know which subscriber of that operator in that country. NAI is used for the non 3GPP like Wi-Fi even if IMSI can be transmitted in this format.

**Note:** IMSI is it stored in SIM card or embedded SIM card in the device.

ii) SUCI (Subecription Permanent Identity)

Suppose there is a scenario where your device is looking for a good signal strength and get connected to the hackers base station. They will track your location and other information easily through the subscriber identity. To prevent this problem in 5G system, the subscription identity as we have saw previously as SUPI is never transmitted unencrypted over the network.Instead, we transmit which we called as SUCI it is concealed because it is encrypted from the SUPI. so the hacker or the middleman will not understand because they don't have decrypted key to decrypt it as it is in encrypted form. 

iii) GUTI (Globally Unique Temporary Identifier) 

When the device connect to the network. The AMF will allocate the temporary identifier to the device and this temporary identifier is used for further communication, so we don't need to transmit the encrypted information often in the network the temporary identifier here is known as GUTI and it has two components GUAMI and TMSI.

