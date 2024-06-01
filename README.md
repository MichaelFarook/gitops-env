
                                    .:^~!!77??77!!~^:.                                    
                               :~7Y5GB##&&&&&&&&&&##BGPY7~:                               
                           .!JPB&&&&&&&&&&&&&&&&&&&&&&&&&&BPJ!:                           
                        .!5B&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&B5!.                        
                      ^JB&&&&&&&&&@@&&&############&&&&&&&&&&&&&&BJ^                      
                    ^Y#&&&&&&@@@&########################&&&&&&&&&&#Y^                    
                  .J#&&&&&&@@&&############BBBBB############&&&&&&&&&#J.                  
                 ~G&&&&&@@@&#########BGP555YYYYYY55PG##########&&&&&&&&G~                 
                7B&&&&&@@&#########G5YYYYYYYYYYYYYYYYYPB#########&&&&&&&B7                
               7#&&&&@@&#########G5YYPGGP5YYYYYYYYYYYYYY5B########&&&&&&&#?               
              !B&&&&@@&#########PYYY5PGGP5YYYYYYYYYYYYYYYYG#########&&&&&&#!              
             :G&&&&@@&#########PYYYYYY55YYYYYYYYYYYYYYYYYYYG#########&&&&&&G:             
          .??Y#&&&&@@#########GYYYYYYYYYYYYYYYYYYYYYYYYYYYY5#########&&&&&&#5J~           
          !#BB#&&&@@&#########5YYYYYYYYYYYYYYYYYYYYYYYYYYYYYB#########&&&&&#B#5           
          !BBB&&&&@@#######BP5PGBBBBG5YJYYYYYYYYYYY5PBB#BBP5YPB#######&&&&&&BB5           
          !BBB&&&&@@######GYG&@@@@@@@@&GYYYYYYYYJ5#@@@@@@@@@#5JG######&&&&&&BB5           
          !BBB&&&&@@#####GY#@@@@Y!!5@@@@BYYYYYYJP@@@@B7!?B@@@@5JG#####&&&&&&BB5           
          !BBB&&&&@@&####55@@@@&:  ^&@@@@5JYYYYJ#@@@@Y   5@@@@BJ5#####&&&&&#BB5           
          ~BBB#&&&@@&####PY&@@@@&GG&@@@@&YJYYYYJG@@@@@BG#@@@@@GJP#####&&&&&#BB5           
           ~~~B&&&&@@&####55#@@@@@@@@@@#5JYYYYYYYG@@@@@@@@@@@GJ5#####&&&&&&B!~:           
              7#&&&&@@&####PYPB&&&&&#BPYJYYYYYYYYJ5G#&&@&&#GYYP#####&&&&&&#?              
               J#&&&&@@&#####GYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYG######&&&&&&#J               
                J#&&&&@@@#####5YYYYYYYYYYYYYYYYYYYYYYYYYYYY5######&&&&&&#J                
                 7B&&&&&&&####PYYYYYYYYYYYYYYYYYYYYYYYYYYYYP####&&&&&&&B7                 
                  ^5#&&&&&&&##GYYYYYYY5JGG5YYYYY5G5YYYYYYYYP##&&&&&&&#5^                  
                    !P&&&&&&&&BYYYYYYY5J7#@&#B##&5J5YYYYYYYG&&&&&&&&P!                    
                      !5#&&&&&#YYYYYYYY57.!J55Y7:!5YYYYYYYYB&&&&&#P!.                     
                        ^JG#&@#5YYYYYYYY5?^    :75YYYYYYYYY#@&#GJ^                        
                          .^?PG5YYYYYYYYY55YJJY55YYYYYYYYY5BP?^.                          
                              ^YYYYYYYYYYYY5555YYYYYYYYYYYJ:                              
                           ..~?J5YYYYYYYYYYYYYYYYYYYYYYYYYY!:.                            
                       .:^~!7J!75YYYYYYYYYYYYYYYYYYYYYYYY5J??7!~:.                        
                               !5Y5JJ5YYYYYYYYYYYYYY5JJ5Y5!                               
                               ^5Y5?J55JYYYYYYYYYYJ55J?5Y5~                               
                               :5Y5!?55?J5YYYYYY5J?55?!5Y5:                               
                               .YY5~?55!J5YYYYYY5J!55?~5YY.                               
                                J55^?55~J5YYYYYY5J~55?:55Y.                               
                               .J55.755:?5Y5!!5Y5J:Y57.Y5J.                               
                         ..:~!7JJJ~ ?5Y.?5YY:.YY5?.Y5? ~JJJ7!~:..                         
                          ...::^^~~?YJ~ J55?  ?55J ~JY?~~^^::...                          
                             ..:::^^~~~?YY?.  .?YY?!~~~^:::..                             
                                .:^~~~!~^.      .^~!~~~^:.                                

# GitOps Repository for ArgoCD

This is the example of my GitOps repository! This repository servers as an illustration of GitOps practices for managing ArgoCD applications.

## Overview

This repository is structured as follows:

- 'applications/': Contains Kubernetes manifests in Helm Chart structure for ArgoCD applications Namespace and SecretsManager. Have unified structure for two environments.
- 'enivornments/': Environment folder with all provided files and manifests for my environments.
- 'environments/production/': The two folders of environments is the same by the structure and files. Here is the applications manifest of ArgoCD app_of_apps - "app.yaml" and "values.yaml" file with global values and values of branc and version of applications.
- 'environments/produciton/environments-values': Folder with values file for application to make orverwride from GitOps repo.

## Prerequisites

Before getting started, make sure you have the following tools installed:

- [kubectl]:(https://kubernetes.io/docs/tasks/tools/install-kubectl/): Kubernetes command-line tool.
- [ArgoCD]:(https://argo-cd.readthedocs.io/en/stable/cli_installation/): Argocd, need to use version >2.5.0
