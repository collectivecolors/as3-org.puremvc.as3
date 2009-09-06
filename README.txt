PureMVC (Standard) releases for use as Git submodules in ActionScript or Flex 
applications.

****************************
* IMPORTING AS A SUBMODULE *
****************************

The following instructions assume that you have a git repository set up on your
application directory.

To import this package into your application, run :

----------
 Commands 
 
$  git submodule add git@github.com:collectivecolors/as3-org.puremvc.as3.git
                     {SOURCE_DIR}/org/puremvc/as3
                     
$  git submodule init

----------

Where :

 {SOURCE_DIR} is your root source folder.  
    
    If your repository is at the root source path then just use the package
    name, org/puremvc/as3 

*********
* NOTES * 
*********

1. We did not create and are not the maintainers of PureMVC.
   Thanks to Cliff Hall at http://futurescale.com for this truly awesome 
   framework!! 
   
2. Please see http://puremvc.org for more information about PureMVC.  If you 
   don't know what it is yet, then you should definitely look further into it.
   It could change the way you program.  It did for us.

3. The official svn repository from which this git repo is based upon is 
   http://svn.puremvc.org/PureMVC_AS3.
   
4. We will try to update this repository as close to actual svn release as 
   possible.  If you notice that this repo is stale then send us a message 
   and we'll update it.