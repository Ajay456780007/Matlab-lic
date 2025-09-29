1.Extract Or Mount R2024b_Windows

2. Run setup.exe go in upper right corner in  "Advanced Options"  select setup mode  "I have a File Installation Key"
     If internet access is absent then required setup mode will be auto-selected and you do not need to select it manually

3. When you will be asked to  "Enter File Installation Key"  enter

Full (without MPS, Polyspace, ...) installation key R2024b:
39676-02743-14813-63132-22122-21739-42724-01237-08353-51560-41813-30272-46436-42021-53831-05395-21684-43572-58789-40638-42099-40160-19797-60670-44428-39867

MPS (Matlab Parallel Server) installation key for R2024b:
20853-09701-14211-48522-39783-14008-29839-47239-06935-59625-19500-19538-18002-61938-30493-02259-56368-30683-57708-47844-15313-37057-18682-48113-00421 

4. When you will be asked to  "Select License File"  select file  "license.lic"  from folder with  R2024a_Windows.iso  file

MATLAB Production Server:
40343-25684-40525-09488

Polyspace Bug Finder + Polyspace Code Prover:
15315-49347-54135-38668

Polyspace Bug Finder Server + Polyspace Code Prover Server:
45569-59682-06610-64133

DO Qualification Kit + IEC Certification Kit:
42610-52008-16202-14804

5.go in Crack copy .dll and apply it on C:\Program Files\MATLAB\R2024b\bin\win64\matlab_startup_plugins\lmgrimpl

6.Done....

7. for polyspace re-run the setup.exe add the above keys too install Polyspace and replace the libmwlmgrimpl from Crack on this path:C:\Program Files\Polyspace\R2024b\bin\win64\matlab_startup_plugins\lmgrimpl
8. run product and point on .lic

Docs for Windows Download : https://ssd.mathworks.com/supportfiles/downloads/R2024b/docisoimages/DOCPKGS24bGR/R2024b_Doc_Windows.iso
