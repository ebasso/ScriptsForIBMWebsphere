# Scripts For IBM WebSphere software

## Portal rc script


Commands:
     ./rc_portal { start | stop | restart } [-WAS_PASSWORD  PASSWORD]
     
 DMgr:
     ./rc_portal { startdmgr | stopdmgr } [-WAS_PASSWORD  PASSWORD]
    
 Node:
     ./rc_portal { startnode | stopnode } [-WAS_PASSWORD  PASSWORD] 
    
 IHS:
     ./rc_portal { startihs | stopihs | statusihs }
 
 IHS Admin CTL:
     ./rc_portal { startadminctl | stopadminctl | statusadminctl }
    
Tools:
      ./rc_portal { serverstatus | kill | killnode | killdmgr }
 
Diagnosis:
      ./rc_portal { generatedumpinfo | checkfilesystem }
