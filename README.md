

# Project: Jargon-core API
<<<<<<< HEAD

### Date:
### Release Version: 4.0.3.1-SNAPSHOT
### git tag: 

=======
#### Date: 04/05/2016
#### Release Version: 4.0.2.6-SNAPSHOT
#### git tag: 
=======
#### Date: 06/07/2016
#### Release Version: 4.0.2.6-RC1
#### git tag: 4.0.2.6-RC1 
>>>>>>> origin/master
#### Developer: Mike Conway - DICE

## News

Work for milestone https://github.com/DICE-UNC/jargon/milestones/4.0.3.1%20second%20tier%20features%20branch


Please go to [[https://github.com/DICE-UNC/jargon]] for the latest news and info.

Jargon-core consists of the following libraries

* jargon-core - base libraries, implementation of the iRODS protocol
* jargon-data-utils - additional functionality for dealing with iRODS data, such as building trees, storing information in iRODS on behalf of applications, and doing diffs between local and iRODS
* jargon-user-tagging - code for using free tagging and other metadata metaphors on top of iRODS
* jargon-user-profile - allows management of user profile and related configuration data in a user home directory
* jargon-ticket - support for ticket processing
* jargon-httpstream - stream http content into iRODS via Jargon
* jargon-ruleservice - support for running and managing rules from interfaces
* jargon-workflow - support for iRODS workflows

## Requirements

* Jargon depends on Java 1.7+
* Jargon is built using Apache Maven2, see POM for dependencies
* Jargon supports iRODS 3.0 through iRODS 3.3.1 community, as well as iRODS 4.1.7 consortium

## Libraries

Jargon-core uses Maven for dependency management.  See the pom.xml file for references to various dependencies.

Note that the following bug and feature requests are logged in GitHub with related commit information [[https://github.com/DICE-UNC/jargon/issues]]

## Changes

#### Remove old thumbnail code #165 

Remove old image thumbnail code that relied on specific 'lifetime library' configuration.  This will later be replaced by a more globally applicable set of tools.  Likely in the jargon-extensions package

####  Add file to string and vice versa to support cloud browser editor #166 

Add file to string and vice versa in FileSamplerService of data utils.  This allows cloud browser to turn a file into an edit pane and store edits to irods.

#### remove resource group from data obj query #197

Remove resc group from data object domain query 
