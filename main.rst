##########################################
Project: Bootstrap/Get started (Genesis)
##########################################

   Project “Bootstrap/Get started” assembles and tests a base set of infrastructure components for OPNFV to run a few example VNFs.  It puts together a single deployment type that can both be used by developers and run in continuous integration.  The goals of the Bootstrap/GetStarted Project is to stand up quickly one or more stacks of components,  learn from their differences and commonality of deployment experience, and feed that back into producing a more flexible framework. Initially the project will focus on a single combination of components. The project will be complete, and hand off to the wider scope “Octopus” project, when CI demonstrably runs and the project can be seen to perform the tasks required of a basic VIM layer.

  * [[get_started/get_started_project_proposal?rev=1418143284|"Bootstrap/Get Started" project proposal - TSC approved version]] (BGS project was approved on Dec/9/2014)
  * [[get_started/get_started_release_plan | Release plan for "Bootstrap/Get-Started"]]
    * [[get_started/get_started_system_state|Target state of the OPNFV system that BGS creates]]
    * [[opnfv_functional_testing/functest_test_cases|List of target functional test cases for OPNFV release #1]]
  * [[get_started/get_started_installer_approach|Base principles of the installation/deployment approach]]
    * [[get_started/installers|List of current deployment tools (installers) investigated]]
    * [[get_started/get_started_work_items|List of candidate work items for "Bootstrap/Get-Started]] [[https://etherpad.opnfv.org/p/bgs|BGS Etherpad - activity tracking]]
    * [[get_started/fuel_status?&#substream_work_areas|Fuel@OPNVFV]]

  * [[get_started/get_started_work_environment|Hardware requirements for "Bootstrap/Get-Started"]] - see also [[pharos/pharos_specification|Pharos specification]]
  * [[get_started/server_resources | "Bootstrap/Get-Started" lab resources]]
  * [[get_started/open_questions | List of open (and closed) questions for "Bootstrap/Get-Started"]]

  * [[meetings?&#bootstrap_get_started_bgs_project_team_meeting | Meeting calendar of "Bootstrap/Get-Started"]]
  * [[meetings/bgs | Meetings of project "Bootstrap/Get-Started" (agendas and minutes)]]



Key Project Facts
==================

{{scrape>https://gerrit.opnfv.org/gerrit/gitweb?p=genesis.git;a=blob_plain;f=INFO;}}

** Additional Contributors **
    * trozet@redhat.com
    * arnaud1.morin@orange.com
    * juan.osorio.robles@ericsson.com
    * psiwczak@mirantis.com
    * rraszuk@mirantis.com
    * rr@mirantis.com
    * matthew.lijun@huawei.com
    * Randy Levensalor (r.levensalor@cablelabs.com)
    * daniel.smith@ericsson.com
    * narinder.gupta@canonical.com

If you would like to contribute to opnfv-genesis please add yourself to the contributors list and contact opnfv-helpdesk@rt.linuxfoundation.org or drop in to #opnfv-bgs on freenode.



** IRC ** : freenode.net #opnfv-bgs ([[http://webchat.freenode.net/?channels=opnfv-bgs]])\\
** Mailing List ** : no dedicated mailing list - use [[https://lists.opnfv.org/mailman/listinfo/opnfv-tech-discuss|opnfv-tech-discuss]] and tag your emails with [bgs] in the subject for easier filtering \\
** Meetings ** :
 
  * Daily (Mon-Fri) hangouts on IRC at 7.30am PDT, [[http://webchat.freenode.net/?channels=opnfv-bgs]]
  * Weekly conference call: Monday, 8am PDT.
    * [[https://global.gotomeeting.com/join/158935301]]
    * Dialin: +1 (872) 240-3412, Access Code: 158-935-301
    * More phone numbers: https://global.gotomeeting.com/158935301/numbersdisplay.html
                
** Repository: ** [[https://gerrit.opnfv.org/gerrit/#/admin/projects/genesis|Gerrit: Project Genesis]] \\
** Changelog: ** [[https://gerrit.opnfv.org/gerrit/#/q/genesis]] \\
** Git Web: ** [[https://gerrit.opnfv.org/gerrit/gitweb?p=genesis.git;a=summary]]


