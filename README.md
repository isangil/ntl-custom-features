ntl-custom-features
===================

These features will override current DEIMS settings -- mimic customization for NTL in DEIMS D6

The modules that begin with "ntl_" are a set of custom modules. We need install in your NTL 
site, enable them.

There will be a series of modules for the NTL type collections. Those create content types
and their name may contain the word Sample.

We tend to keep these modules in a folder that is not in the "profile", as these are not part 
of theDEIMS profile.  For example, you can place them under "sites/default/modules" 
(note im not saying sites/all/modules - you may have to make that modules directory yourself)

In general these modules override some configuration settings, add fields and content types.

Specifically, we enhance the DEIMS Person module.  This is a feature that will override the 
existing feature -- you may try overwriting the "profiles/deims/modules/features/deims_person" 
module. Visit the "features" dashboard to activate it, or just run cron once you drop it there.

The other three can be enabled by visiting the "modules" page




