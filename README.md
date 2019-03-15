Supplimentary code for the Drug Perturbation Network

Things added so far:  
1.) Interactome_Construction_And_Analysis  
&nbsp;&nbsp;&nbsp;- Create human interactome (currently using the Menche DB)  
&nbsp;&nbsp;&nbsp;- Make a basic description of the PPI (e.g. #nodes, #edges, diameter etc.)  
2.) Drug_Target_Annotations  
&nbsp;&nbsp;&nbsp;- use of DrugBank, PubChem and ChEMBL to extract targets  
3.) Drug_Properties  
&nbsp;&nbsp;&nbsp;- Extraction of drug properties:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.) ATC  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.) GO Annotations  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.) Disease  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.) KeGG Pathways  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.) SIDER (known effects)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.) Offside (known off sides)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.) Drug Properties (physico-chemical properties)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8.) Enzymes, Transporters and Carriers  
4.) CLOUD_Description  
&nbsp;&nbsp;&nbsp;- Describe the CLOUD library in target, pathways etc.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.) Target and target classes    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.) ATC classes covered   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.) KeGG pathways  
5.) PPI_Analysis  
&nbsp;&nbsp;&nbsp;- Analyse how the CLOUD drugs perturb the human PPI  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.) Drug perturbations and PPI degree  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.) Drug perturbations and PPI centrality   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.) LCC size of drug perturbations  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.) Shortest paths of drug perturbations  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.) Calculate overlap between two drug modules  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.) Localization/Separation and GO term similarity  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.) Localization/Separation and Disease similarity  
5.) ATC_Analysis  
&nbsp;&nbsp;&nbsp;- Analyse how the CLOUD drugs separation behaves with ATC  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.) ATC to Sab  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.) Sab_Overview  





6.) ImageAnalysis  
&nbsp;&nbsp;&nbsp;- Tools and code to go from images to final feature strings  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.) Create ImageInput File + sample  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.) Image quality check  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.) Normalize Plates (remove plate effects)    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.) Normalize to POC  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.) Calculate Coefficient of Variato (and replicate correlation)     
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.) Check effect size per feature  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.) Check feature correlation    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8.) Create drug vectors