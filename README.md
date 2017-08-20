# Certable - Opt-in content mogrification proposal

**The Certable Project** aims to create a base reference for operating system and embedded device manufacturers to enable opt-in security certificate overrides which allow for content filtering, data loss prevention, and more introspective personal security.

This project proposes that there could and should be a simplified mechanism for all current major desktop (Windows, MacOs, The Linux's), mobile operating systems (Windows, iOS, Android) and embedded home devices (Amazon Echo, Google Home, Your Fridge) to negotiate a valid certificate manager for a specific domain or domain set.

Domains or domain sets should be tagged with specific metadata through a global community and stored in a highly reliable location.  This content could include tags related to banking, explicit content, email communication, and so on.  Content can further be analyzed for hashable content that may show certain private information was transmitted or received.

A simple mechanism should be put in place to allow private firewalls, researchers, and Internet guardians the means to associate an administrative request for an override between access devices and endpoint devices.

Doing so could allow restricted and moderated access to content otherwise unavailable or deemed inappropriate for any specific audience.  Access devices will be able to modify (mogrify) content requests between end devices and content providers to restrict or report content access and provide analytics.

TLS/SSL certificate management is often done at the operating system level.  In some situations, like some Java application implementations, a proprietary certificate manager is used.  Conforming to Certable design standards would allow the operating system and/or compatible security libraries used by applications the means to process access requests for filtered content management.

## What this means for Internet guardians

More to come...

## What this means for the audience

Take Spotify or Youtube for instance.  In both situations there can and will most likely be a community rating and tagging system for content.  What we lack is the mechanism to review content as a guardian.  Once ratings become reliable then content can be searched for and ultimately filtered before search requests return to the end user application.  Instead of seeing "censored" or "blocked".. content is simply not found.

Sadly this means, for Spotify, that Top 50 Pop Hits playlist will contain roughly 2 songs.
