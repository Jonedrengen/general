Box Link: Box/LIU-PRICE\ LAB/Bioinformatics/Host_Elements/main_trainingset/

Decision made Aug 21 2024 (Dan+Maliha+team) see slack for details
retain only 49 FZEC from BigFUTI and 1 from DCFUTI as Test (training=0). Delete the rest of the FZEC from BigFUT and DCFUTI
it has 7 contaminated meats as Test (training=0) ok-ed by Dan
BIGFUT-DCFUTI (reduced FZEC) is here -> ref_file/070924_any_element_presence_input_bigfuti_dcfuti.xlsx

Update 08/20/25 -- Edward Sung
082025_any_element_presence_input_bigfuti_dcfuti.csv
	This updates the columns to be Host labels with kmodes clustering [1 or 2]
	Updates the Presence Absence of the N=17 Elements based on mmseq2 results and Olivia's CE presentation rule sets

Update 10/21/25 -- Edward Sung
102125_any_element_presence_input_bigfuti_dcfuti_ExcludesBeef.csv
	This version created does not include beef catagory in training, thus cannot predict for beef class.
	R Code base will reflect this as well.

Note from before, these samples were originally dropped during Julio Testing, where these didn't return a clustering ID (See Slack).
106_CN_03_B20_M2_C5_P2
30_CN_07_B26_M3_C9_P2
34_CN_04_B28_M3_C8_P2
34_CN_06_B28_M3_C8_P2
39_CN_07_B20_M2_C6_P1
40_CN_06_B20_M2_C6_P2
71_CN_18_B38_M2_C5_P1
Escherichia_coli_105_CN_08_B6_M2_C5_P1_GACCTTAG_L003
Escherichia_coli_34_CN_03_B28_M3_C8_P2
Escherichia_coli_41_CN_08_B6_M2_C7_P1_GCTAACTC_L004
Escherichia_coli_57_CN-08_B30_M1_C3_P1
FMC_UTI_01918