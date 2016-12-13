# Electronic Dispensing Applications (EDA)
Under the responsibility of the National Pharmacies Association (pharmacies perspective);

## System Requirements
In Portugal, electronic prescribing is the procedure for issuing prescriptions via computer
applications certified by the SPMS - Shared Services of the Ministry of Health, EPE, or under its
responsibility, which is regulated by Decree nº 198/2011 of 18 May from the Ministry of
Health. For further information, read the information contained in the following links (in
Portuguese):
- Portaria nº 198/2011 de 18 de Maio do Ministério da Saúde
http://www.sg.min-saude.pt/NR/rdonlyres/B9EBB192-952E-4C97-94FD-
6B54A9F75A58/26505/Portaria198_2011_RME.pdf
- Prescrição Eletrónica de Medicamentos e Produtos de Saúde: Especificação dos Serviços
para integração com a Sistema Central de Prescrições, SPMS, Março de 2013 
 MESW – Software Engineering Principles and Paradigms – 2016/17 Pg. 2
http://www.spms.pt/wpcontent/uploads/2012/12/PEM_ServicosPrescri%C3%A7%C3%A3o_ET-v1.2.pdf
- Página da SPMS sobre Prescrição Eletrónica de Medicamentos com mais informação:
http://spms.min-saude.pt/2013/11/pem-prescricao-eletronica-medica-2/
- Página do Infarmed sobre Prescrição Eletrónica de Medicamentos:
http://www.infarmed.pt/portal/page/portal/INFARMED/MEDICAMENTOS_USO_HUMANO
/PRESCRICAO_DISPENSA_E_UTILIZACAO/PRESCRICAO_ELECTRONICA_MEDICAMENTOS
- http://www.jornaldenegocios.pt/economia/saude/detalhe/farmacias_estao_totalmente_
preparadas_para_a_receita_electronica
- http://spms.min-saude.pt/product/receita-sem-papel/

Electronic prescribing applications should submit the prescriptions to the Prescriptions Central
System (PCS), which contains the National Prescriptions Database (NPDB) and provides web
services for the safe registration of prescriptions based on credentials (login and password)
provided within the application certification process. All the prescriptions of a particular month
should be sent to the PCS up to the second day of the following month. If possible, this
submission should be made at the time of prescription. When the service returns an error or is
unavailable, prescriptions must be resubmitted later. Prescriptions may be cancelled (by their
authors) within 30 days after the date of prescription.
The prescription registration service (of the PCS) validates, among other, the following data:
identification of the prescribing physician, by comparing with information provided
periodically by the Medical Association; prescription site identification (health facility, clinic,
etc.); user identification (in case of prescriptions to be partially paid by the National Health
System - NHS), comparing with the database of the National Users Registry (NUR) of the NHS;
drug identification, comparing with the database maintained by Infarmed (the national
authority for medical drugs).
Users registered in the NHS (NUR) may request via the Health Portal credentials that allow
them to consult not only their identification data as well as the prescriptions issued in their
name.
The Invoice Validation Center (IVC) of the National Health Service accesses monthly the PCS to
extract the information about prescriptions produced in the previous month, in order to
compare this information with the information from invoices and prescriptions submitted by
pharmacies.
Currently there are several dozens of certified electronic prescribing applications from
different vendors, for different environments: Software as a Service (SaaS) Web applications
(not requiring installation), applications for installation on personal computers and
applications for installation on mobile devices (such as iPAD).
These applications typically offer the following features to their users (doctors):
- electronic prescription (involving site selection, user selection, drug selection, dosage and
other information; submit and print) ;
- consultation , cancellation and reprint of previously issued prescriptions;
- export prescriptions issued to the PDB (when not performed immediately on prescription);
- access to the National Users Registry of the NHS (NUR), via a Web Service, to obtain all the
information of a new user based solely on the number, avoiding manual entry of
information;
- access to the database of medical drugs maintained by Infarmed (via a Web Service) in real

time at the point of prescribing , or for download (and offline usage).
Through certified applications, pharmacies may have access to the SPC for dispensing
prescriptions for a particular user, as well as access to the IVC for sending electronic invoices.
Patients may use Personal Health Applications (PHA) to manage their personal health and keep
track of prescriptions and other health related information.