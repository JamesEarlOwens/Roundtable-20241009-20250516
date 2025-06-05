This repository contains 2 datasets on 2 files: 
  FILE 1: panelist_data_100924-051625 FORMATTED.csv 
  FILE 2: panelists_by_episodes_distrib_100924-051625 FORMATTED.csv

1. The file panelist_data_100924-051625 FORMATTED.csv contains data on all panelists appearing in all episodes from 10/09/24 - 5/16/25. 
Data fields are as follows:
field             Value  Descr. 
panelist  Panelist name
subject_expert		1=Yes  Is this person an expert on the Middle East? (Did they publish on the topic OR carry out policy or research work in the region for many years?
academic		      1=Yes  Does/did this person work as a professor, instructor or researcher at an institution of higher learning?journalist	defense_co_rep	dod_dhs	intl_rts_aid_org	palestinian	mena	w_bipoc	gender	elect_emply_polparty	nys_dem	race_details
journalist		    1=Yes  Does/did the panelist produce news, either independently or for a news organization?
defense_co_rep		1=Yes  Do/did they work for a corporation in the defense sector?
dod_dhs		        1=Yes  Does/did the person work for any FEDERAL defense or 'national security' agency? (DoD, DHS, NSA, NSC, CIA, DIA, Pentagon/US military?
intl_rts_aid_org	1=Yes  Does/did they work for an INTERNATIONAL human rights or aid organization?
palestinian		    1=Yes  Are they Palestinian?
mena		          1=Yes  Are they of Middle East/North African ancestry?
w_bipoc		        W/B    For white use 'W', for non-White use 'B' (for BIPoC)
gender		        M/F/N  M, F. or N (non-bin, trans, intersex, etc)
elect_emply_polparty	DEM/GOP	Political party affiliation, or that of their government employer
nys_dem		        1=Yes  Are they affiliated with the New York State Democratic Party?
Race_details		  Detail coding for race:
                      W	Whites
                      AA	African Americans
                      As	Asians
                      L	Latino/a/x
                      M	MENA
                      B	non-US (Afro Caribbean, etc.)


2. The file panelists_by_episodes_distrib_100924-051625 FORMATTED.csv contains data on all episodes from 10/09/24 - 5/16/25.
Data fields are as follows:
date	Date of episode
panelist_name1	
panelist_name2	
panelist_name3	
panelist_name4	
panelist_name5	
panelist_name6	
panelist_name7	
panelist_name8	
subject_expert_count	  # of Middle East experts in this episde
academic_count	        # of academics in this episode
academic_admin_count	  # of higher ed administrators
student_count	          # of students in this episode
pal_student_count	      # of Palestinian students
journalist_count	      # of journalists in this episode
defense_co_rep_count	  # of Defense Corporation representatives
dod_dhs_count	          # of guest with backgrounds in Department of Defense, Dept. Homeland Sec., Nat'l Sec. Council, or other US gov military organization
non_def_corp_rep_count	# of Corporate reps from non-military companies
intl_rts_aid_org_count	# of International rights or aid org. reps
palestinian_count	      # of Palestinians in this episode
mena_count	            # of menas in this episode
w_count	                # of Whites in this episode
bipoc_count	            # of BIPoC people in this episode
f_gender_count	        # of female
m_gender_count	        # of male
gop_count	              # of gops in this episode
dem_count	              # of dems in this episode
nys_dem_count	          # of New York State Dem. Party guests
total_panelists	        # of totals in this episode
PROP WHITE            	Proportion of Whites in this episde as percentage
![image](https://github.com/user-attachments/assets/5ce14fe3-0d6c-46e2-aa09-da0e1f5ea17a)
