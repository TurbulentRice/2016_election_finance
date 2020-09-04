# 2016_election_finance
Expenditure data of the top four spending campaigns during the 2016 U.S. presidential elections, from 2015-2016. Data culled from https://www.fec.gov/data/.

Datasets have been cleaned of irrelevant rows and empty/duplicate columns:
- Contribution refunds (disbursement_type: 22R, 22Y, 22Z) have been excluded, as they aren't counted as "expenses" for our purposes.
- Columns with obvious empty, duplicate or extraneous data have beend dropped. Dropped columns are:
['payee_prefix', 'payee_suffix', 'payee_employer',
'payee_occupation', 'ref_disp_excess_flg', 'comm_dt',
'payee_last_name', 'payee_first_name', 'payee_middle_name',
'category_code', 'category_code_full', 'conduit_committee_name',
'conduit_committee_street1', 'conduit_committee_street2', 'conduit_committee_city',
'conduit_committee_state', 'conduit_committee_zip', 'spender_committee_type',
'spender_committee_org_type', 'spender_committee_designation', 'original_sub_id',
'back_reference_transaction_id', 'back_reference_schedule_id', 'semi_annual_bundled_refund',
'candidate_name', 'candidate_office', 'candidate_office_description',
'candidate_office_district', 'candidate_id', 'candidate_first_name',
'candidate_last_name', 'candidate_middle_name', 'candidate_prefix',
'candidate_suffix', 'candidate_office_state', 'candidate_office_state_full',
'election_type_full', 'beneficiary_committee_name', 'national_committee_nonfederal_account',
'unused_recipient_committee_id', 'two_year_transaction_period', 'schedule_type',
'schedule_type_full', 'sub_id', 'pdf_url',
'load_date', 'link_id', 'disbursement_type_description',
'image_number', 'memo_code', 'memo_code_full', 'amendment_indicator_desc',
'fec_election_year', 'line_number', 'line_number_label']
