# Security & privacy self-review for restrictOwnAudio option for getDisplayMedia

This document answers the questions from [Self-Review Questionnaire: Security and Privacy](https://w3c.github.io/security-questionnaire/).

## [01. What information does this feature expose, and for what purposes?](https://w3c.github.io/security-questionnaire/#purpose) 
The feature will expose restrictOwnAudio availability. Web pages can make decisions based on restrictOwnAudio availability.
## [02.  Do features in your specification expose the minimum amount of information necessary to implement the intended functionality?](https://w3c.github.io/security-questionnaire/#minimum-datahttps://w3c.github.io/security-questionnaire/#minimum-data)
Yes. 
## [03.  Do the features in your specification expose personal information, personally-identifiable information (PII), or information derived from either?](https://w3c.github.io/security-questionnaire/#personal-data)
No.
## [04.  How do the features in your specification deal with sensitive information?](https://w3c.github.io/security-questionnaire/#sensitive-data)
The feature does not deal with sensitive information.
## [05.  Does data exposed by your specification carry related but distinct  information that may not be obvious to users?](https://w3c.github.io/security-questionnaire/#hidden-data)
No.
## [06.  Do the features in your specification introduce state that persists across browsing sessions?](https://w3c.github.io/security-questionnaire/#persistent-origin-specific-state)
No.
## [07.  Do the features in your specification expose information about the underlying platform to origins?](https://w3c.github.io/security-questionnaire/#underlying-platform-data)
No.
## [08.  Does this specification allow an origin to send data to the underlying platform?](https://w3c.github.io/security-questionnaire/#send-to-platform)
The restrictOwnAudio setting will be sent to the underlying platform as a boolean.
## [09.  Do features in this specification enable access to device sensors?](https://w3c.github.io/security-questionnaire/#sensor-data)
No.
## [10.  Do features in this specification enable new script execution/loading mechanisms?](https://w3c.github.io/security-questionnaire/#string-to-script)
No.
## [11.  Do features in this specification allow an origin to access other devices?](https://w3c.github.io/security-questionnaire/#remote-device)
No.
## [12.  Do features in this specification allow an origin some measure of control over a user agent's native UI?](https://w3c.github.io/security-questionnaire/#native-ui)
No.
## [13.  What temporary identifiers do the features in this specification create or expose to the web?](https://w3c.github.io/security-questionnaire/#temporary-id)
None.
## [14.  How does this specification distinguish between behavior in first-party and third-party contexts?](https://w3c.github.io/security-questionnaire/#first-third-party)
The behaviour is the same.
## [15.  How do the features in this specification work in the context of a browser’s Private Browsing or Incognito mode?](https://w3c.github.io/security-questionnaire/#private-browsing)
The behaviour is the same.
## [16.  Does this specification have both "Security Considerations" and "Privacy Considerations" sections?](https://w3c.github.io/security-questionnaire/#considerations)
This is part of a [larger spec](https://w3c.github.io/mediacapture-screen-share) which has several sections related to Security and Privacy that cover the security and privacy issues related to this feature.
The explainer has extra details specific to this addition.
## [17.  Do features in your specification enable origins to downgrade default security protections?](https://w3c.github.io/security-questionnaire/#relaxed-sop)
No.
## [18.  What happens when a document that uses your feature is kept alive in BFCache (instead of getting destroyed) after navigation, and potentially gets reused on future navigations back to the document?](https://w3c.github.io/security-questionnaire/#bfcache)
The Screen capture this feature modifies is stopped and is not recoverable.
## [19.  What happens when a document that uses your feature gets disconnected?](https://w3c.github.io/security-questionnaire/#non-fully-active)
It will behave the same as a BFCached document. 
## [20.  Does your spec define when and how new kinds of errors should be raised?](https://w3c.github.io/security-questionnaire/#error-handling)
There are no new errors.
## [21.  Does your feature allow sites to learn about the user's use of assistive technology?](https://w3c.github.io/security-questionnaire/#accessibility-devices)
No.
