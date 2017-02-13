# gcm-impacta
# apache http server:
Changes with Apache 2.4.25

  *) Fix some build issues related to various modules.
     [Rainer Jung]
#Tomcat:
  Cluster
    add	Make the accessTimeout configurable in BackupManager. The accessTimeout is used as a timeout period for PING in replication map. (kfujino)
  Web applications
    fix	Ensure the ASF logo image is correctly displayed in docs and host-manager applications. (violetagg)

 #Eclipse:
 Fixes:
 * Exclude from compare view files with identical content in case they're reported (bug 508237)
 * Two-way and three-way compare should display "deletion+addition" pairs properly when they're reported instead of "replacement" (bug 508236)
   + special thanks for the contribution to Florent Angebault
 * Proper SVNDiffStatus order when deletion and addition are reported for the same nodes (bug 508235)
 * "Ignore ancestry" option for compare with branch/tag/URL (bug 508231)
   + special thanks to Florent Angebault
 * Update from History view and Synchronize view don't change states in another view (bug 505370)
 * Issue in SVNLightweightDecorator when decorating model elements (resource==null) (bug 502505)
 * [scalability] Resource listener listens to changes on ignored files (bug 505360)
   + special thanks for the contribution to Andrey Loskutov
 * Performance improvements for ResourceStatesChangedEvent (bug 506811)
   + special thanks for the contribution to Andrey Loskutov
 * [scalability] SVN update takes hours if "Synchronize" view is opened (bug 504058)
   + special thanks for the contribution to Andrey Loskutov
 * Performance improvements for AbstractSVNSubscriber (bug 506777)
   + special thanks for the contribution to Andrey Loskutov
 * Performance improvements for SVNUtility (bug 506763)
   + special thanks for the contribution to Andrey Loskutov
 * Performance improvements for RemoteStatusCache (bug 506762)
   + special thanks for the contribution to Andrey Loskutov
 * Performance improvements for UpdateSubscriber (bug 506760)
   + special thanks for the contribution to Andrey Loskutov
 * Performance improvements for FileUtility (bug 506757)
   + special thanks for the contribution to Andrey Loskutov
 * Compilation issue with older platform versions (bug 506756)
   + special thanks for the contribution to Andrey Loskutov
 * Error in fix for the bug 282000 causes performance issues (bug 506785)
 * Installation instructions in 'help' are out of date (bug 503327)
 * Separate requirements page is unnecessary in 'help' (bug 503329)
 * Remove org.eclipse.team.svn.resource.ignore.rules.jdt bundle (bug 505611)
 * Correct "management instructions" help page (bug 505119)
 * Grammar correction on the "Mylyn" help page (bug 505115)
 * Update Subversive modules overview (bug 505089)
 * Grammar corrections on the "Supported protocols" page (bug 505006)
 * Grammar corrections on the "Features" page (bug 504927)
 * Update Subversive architecture overview (bug 503542)
 * Linux notes are partially out of date and in need of grammar corrections (bug 503330)
 * FAQ section in plug-in 'help' requires actualization (bug 503325)
 * Subversive tries to connect to repository for Compare With -> Base from Working Copy (bug 501030)
 * Deleting multiple files is very slow on large projects (bug 501032)
 
