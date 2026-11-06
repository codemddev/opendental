# code.md
Machine-generated structural truth for this repository.
Used by coding agents to understand architecture, flow, and dependencies.

Generated for local-path/opendental-668787b1 from direct repository evidence only. No LLM summaries, feature catalog, embeddings, vectors, train pairs, or model-layer files are used.
Only deterministic sections requested by the user are included.

## api_routes
Evidence: deterministic Python decorator parsing plus exact JavaScript/TypeScript route-call parsing from source files.
_No rows found from the available direct evidence._

## entry_points
Evidence: exact `entry_points` array from the selected callgraph artifact.
_No rows found from the available direct evidence._

## risky_functions
Evidence: callgraph in-degree count only. Higher in-degree means more callers in the extracted graph.
| Node | In-degree | Out-degree | Total degree |
| --- | --- | --- | --- |
| OpenDentBusiness.Db.NonQ | 3403 | 0 | 3403 |
| OpenDental.MsgBox.Show | 2220 | 2 | 2222 |
| OpenDental.FolderBrowserDialog.ShowDialog | 2208 | 2 | 2210 |
| OpenDental.Lan.g | 1989 | 2 | 1991 |
| OpenDentBusiness.Db.GetTable | 1606 | 1 | 1607 |
| CodeBase.ODPrimitiveExtensions.IsNullOrEmpty | 1417 | 0 | 1417 |
| CodeBase.ODThread.Join | 1148 | 1 | 1149 |
| OpenDental.UI.Button.Button | 1138 | 1 | 1139 |
| OpenDentBusiness.Meth.GetVoid | 1092 | 4 | 1096 |
| OpenDentBusiness.InsPlanSubstitution.AreEqual | 1065 | 0 | 1065 |
| OpenDentBusiness.Meth.GetObject | 1033 | 2 | 1035 |
| OpenDental.FormSheetDefEdit.Label | 1014 | 0 | 1014 |
| OpenDental.FormODBase.InitializeLayoutManager | 986 | 2 | 988 |
| OpenDental.Lan.F | 888 | 4 | 892 |
| OpenDentBusiness.Lans.g | 815 | 2 | 817 |
| OpenDentBusiness.PrefC.GetBool | 715 | 1 | 716 |
| UnitTestsCore.PatientT.CreatePatient | 708 | 8 | 716 |
| OpenDentBusiness.Security.IsAuthorized | 682 | 9 | 691 |
| CodeBase.ListTools.In | 537 | 0 | 537 |
| OpenDentBusiness.PrefC.GetString | 533 | 1 | 534 |
| OpenDentBusiness.SecurityLogs.MakeLogEntry | 520 | 11 | 531 |
| UnitTestsCore.ProcedureT.CreateProcedure | 514 | 4 | 518 |
| OpenDentBusiness.OdSqlParameter.OdSqlParameter | 501 | 0 | 501 |
| OpenDental.UI.GridOD.GridOD | 475 | 2 | 477 |
| DataConnectionBase.SOut.StringParam | 465 | 1 | 466 |
| UnitTestsCore.ProviderT.CreateProvider | 454 | 2 | 456 |
| fyiReporting.RDL.VBFunctions.Replace | 442 | 0 | 442 |
| OpenDentBusiness.Meth.GetLong | 438 | 4 | 442 |
| CodeBase.MiscUtils.ForEach | 433 | 0 | 433 |
| OpenDentBusiness.ReplicationServers.GetKey | 421 | 3 | 424 |

## top_connected_nodes
Evidence: total callgraph degree count only.
| Node | Total degree | In-degree | Out-degree |
| --- | --- | --- | --- |
| OpenDentBusiness.Db.NonQ | 3403 | 3403 | 0 |
| OpenDental.MsgBox.Show | 2222 | 2220 | 2 |
| OpenDental.FolderBrowserDialog.ShowDialog | 2210 | 2208 | 2 |
| OpenDental.Lan.g | 1991 | 1989 | 2 |
| OpenDentBusiness.Db.GetTable | 1607 | 1606 | 1 |
| CodeBase.ODPrimitiveExtensions.IsNullOrEmpty | 1417 | 1417 | 0 |
| CodeBase.ODThread.Join | 1149 | 1148 | 1 |
| OpenDental.UI.Button.Button | 1139 | 1138 | 1 |
| OpenDentBusiness.Meth.GetVoid | 1096 | 1092 | 4 |
| OpenDentBusiness.InsPlanSubstitution.AreEqual | 1065 | 1065 | 0 |
| OpenDentBusiness.Meth.GetObject | 1035 | 1033 | 2 |
| OpenDental.FormSheetDefEdit.Label | 1014 | 1014 | 0 |
| OpenDental.FormODBase.InitializeLayoutManager | 988 | 986 | 2 |
| OpenDental.Lan.F | 892 | 888 | 4 |
| OpenDentBusiness.Lans.g | 817 | 815 | 2 |
| OpenDentBusiness.PrefC.GetBool | 716 | 715 | 1 |
| UnitTestsCore.PatientT.CreatePatient | 716 | 708 | 8 |
| OpenDentBusiness.Security.IsAuthorized | 691 | 682 | 9 |
| CodeBase.ListTools.In | 537 | 537 | 0 |
| OpenDentBusiness.PrefC.GetString | 534 | 533 | 1 |
| OpenDentBusiness.SecurityLogs.MakeLogEntry | 531 | 520 | 11 |
| UnitTestsCore.ProcedureT.CreateProcedure | 518 | 514 | 4 |
| OpenDentBusiness.OdSqlParameter.OdSqlParameter | 501 | 501 | 0 |
| OpenDental.UI.GridOD.GridOD | 477 | 475 | 2 |
| DataConnectionBase.SOut.StringParam | 466 | 465 | 1 |
| UnitTestsCore.ProviderT.CreateProvider | 456 | 454 | 2 |
| OpenDentBusiness.Meth.GetLong | 442 | 438 | 4 |
| fyiReporting.RDL.VBFunctions.Replace | 442 | 442 | 0 |
| CodeBase.MiscUtils.ForEach | 433 | 433 | 0 |
| OpenDentBusiness.ReplicationServers.GetKey | 424 | 421 | 3 |

## complex_functions
Evidence: callgraph out-degree count only. Higher out-degree means the node calls more extracted targets.
| Node | Out-degree | In-degree | Total degree |
| --- | --- | --- | --- |
| Appointments.TryMoveAppointment | 133 | 2 | 135 |
| OpenDentBusiness.Cache.GetCacheDs | 117 | 1 | 118 |
| OpenDental.ProgramL.Execute | 110 | 9 | 119 |
| OpenDentBusiness.Cache.FillCache | 107 | 1 | 108 |
| OpenDentBusiness.X837_5010.WriteFunctionalGroup | 79 | 1 | 80 |
| OpenDental.FormOpenDental.FormOpenDentalShown | 79 | 2 | 81 |
| module.MobileWeb.scripts.jqueryui.jquery.ui.datepicker | 79 | 0 | 79 |
| OpenDentBusiness.Eclaims.Canadian.SendClaim | 67 | 3 | 70 |
| OpenDental.FormPatientEdit.butOK_Click | 64 | 0 | 64 |
| OpenDentBusiness.SheetFiller.FillFieldsInStaticText | 61 | 1 | 62 |
| OpenDental.ControlChart.Tool_eRx_Click | 61 | 4 | 65 |
| OpenDentBusiness.AccountModules.GetAccount | 59 | 20 | 79 |
| fyiReporting.RDL.Parser.MatchFuncIDent | 59 | 1 | 60 |
| OpenDental.FormProcEdit.SaveAndClose | 53 | 3 | 56 |
| OpenDental.AppointmentL.BreakApptHelper | 49 | 5 | 54 |
| OpenDental.FormReportsMore.OpenReportHelper | 47 | 2 | 49 |
| OpenDentBusiness.X837_4010.WriteFunctionalGroup | 46 | 1 | 47 |
| OpenDental.ControlAppt.pinBoard_ApptMovedFromPinboard | 46 | 0 | 46 |
| OpenDental.FormApptEdit.FormApptEdit_Load | 46 | 0 | 46 |
| OpenDental.FormPatientEdit.FormPatientEdit_Load | 46 | 0 | 46 |
| OpenDentBusiness.AccountModules.CreateClaim | 45 | 2 | 47 |
| OpenDental.ControlTreat.CreateDocument | 44 | 6 | 50 |
| OpenDentBusiness.X837_5010.Validate | 43 | 1 | 44 |
| OpenDental.ControlChart.FillPtInfo | 43 | 4 | 47 |
| OpenDental.FormApptEdit.UpdateListAndDB | 43 | 7 | 50 |
| OpenDentBusiness.ChartModules.GetProgNotes | 42 | 7 | 49 |
| OpenDentBusiness.WebServiceMainHQProxy.GetEServiceSetupFull | 41 | 3 | 44 |
| OpenDental.ControlTreat.LoadActiveTP | 41 | 4 | 45 |
| TestCanada.FormTestCanada.butScripts_Click | 40 | 0 | 40 |
| OpenDentBusiness.ChartModules.GetAll | 39 | 1 | 40 |

## file_dependencies
Evidence: direct file graph edges from the file graph artifact.
| Source file | Target file | Evidence reason |
| --- | --- | --- |
| CentralManager/Db/CentralConfigHelper.cs | CodeBase/Utilities/ODFileUtils.cs | function call, inferred call |
| CentralManager/Db/CentralConfigHelper.cs | CodeBase/Utilities/PasswordVaultWrapper.cs | function call, inferred call |
| CentralManager/Db/CentralConfigHelper.cs | OpenDental/ReportingForRdl/Allocators/MyAllocator1/SupportingCode/GuarantorLedgerItemsCollection.cs | function call, inferred call |
| CentralManager/Db/CentralConnectionHelper.cs | DataConnectionBase/DataConnection.cs | function call, inferred call |
| CentralManager/Db/CentralConnectionHelper.cs | OpenDentBusiness/Cache/Cache.cs | function call, inferred call |
| CentralManager/Db/CentralConnectionHelper.cs | OpenDentBusiness/Data Interface/CentralConnections.cs | function call, inferred call |
| CentralManager/Db/CentralConnectionHelper.cs | OpenDentBusiness/Remoting/RemotingClient.cs | function call, inferred call |
| CentralManager/Db/CentralGroupPermissions.cs | OpenDentBusiness/Data Interface/GroupPermissions.cs | function call, inferred call |
| CentralManager/Db/CentralGroupPermissions.cs | RdlEngine/Definition/Rows.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | CentralManager/Db/CentralConnectionHelper.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | CentralManager/Db/CentralGroupPermissions.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | CentralManager/Db/CentralUserGroups.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | CentralManager/Db/CentralUserods.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | CodeBase/Utilities/ODPrimitiveExtensions.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | CodeBase/Utilities/ODThread.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Cache/PrefC.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/AlertSubs.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/Clinics.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/GroupPermissions.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/Prefs.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/SecurityLogs.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/Signalods.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/UserGroupAttaches.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/UserGroups.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/Data Interface/Userods.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/TableTypes/AlertSub.cs | function call, inferred call |
| CentralManager/Db/CentralSyncHelper.cs | OpenDentBusiness/TableTypes/UserGroup.cs | function call, inferred call |
| CentralManager/Db/CentralUserGroups.cs | OpenDentBusiness/Data Interface/UserGroups.cs | function call, inferred call |
| CentralManager/Db/CentralUserGroups.cs | RdlEngine/Definition/Rows.cs | function call, inferred call |
| CentralManager/Db/CentralUserods.cs | OpenDentBusiness/Data Interface/Userods.cs | function call, inferred call |
| CentralManager/Db/CentralUserods.cs | RdlEngine/Definition/Rows.cs | function call, inferred call |
| CentralManager/FormCentralChooseDatabase.cs | CentralManager/Db/CentralConfigHelper.cs | function call, inferred call |
| CentralManager/FormCentralChooseDatabase.cs | OpenDentBusiness/Db Multi Table/Security.cs | function call, inferred call |
| CentralManager/FormCentralChooseDatabase.cs | OpenDentBusiness/Remoting/Meth.cs | function call, inferred call |
| CentralManager/FormCentralChooseDatabase.cs | OpenDental/Forms/FormSheetDefEdit.cs | function call, inferred call |
| CentralManager/FormCentralChooseDatabase.cs | OpenDental/Logic/Lan.cs | function call, inferred call |
| CentralManager/FormCentralChooseDatabase.cs | OpenDental/UI/Button.cs | function call, inferred call |
| CentralManager/FormCentralConnectionEdit.cs | CentralManager/FormCentralConnectionEdit.designer.cs | function call, inferred call |
| CentralManager/FormCentralConnectionEdit.cs | OpenDentBusiness/Data Interface/CentralConnections.cs | function call, inferred call |
| CentralManager/FormCentralConnectionEdit.designer.cs | OpenDental/Forms/FormSheetDefEdit.cs | function call, inferred call |
| CentralManager/FormCentralConnectionEdit.designer.cs | OpenDental/UI/Button.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.Designer.cs | OpenDentBusiness/Remoting/Meth.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.Designer.cs | OpenDentBusiness/UI/GridOD.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.Designer.cs | OpenDental/Forms/FormSheetDefEdit.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.Designer.cs | OpenDental/UI/Button.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.cs | CentralManager/FormCentralConnectionGroupEdit.Designer.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.cs | OpenDentBusiness/Data Interface/CentralConnections.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.cs | OpenDentBusiness/Data Interface/ConnGroupAttaches.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.cs | OpenDentBusiness/Data Interface/ConnectionGroups.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroupEdit.cs | OpenDentBusiness/Data Interface/Lans.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.Designer.cs | OpenDentBusiness/Remoting/Meth.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.Designer.cs | OpenDentBusiness/UI/GridOD.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.Designer.cs | OpenDental/Forms/FormSheetDefEdit.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.Designer.cs | OpenDental/UI/Button.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | CentralManager/FormCentralConnectionGroupEdit.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | CentralManager/FormCentralConnectionGroups.Designer.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDentBusiness/Cache/PrefC.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDentBusiness/Data Interface/ConnGroupAttaches.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDentBusiness/Data Interface/ConnectionGroups.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDentBusiness/Data Interface/Lans.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDentBusiness/Data Interface/Prefs.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDental/Logic/Lan.cs | function call, inferred call |
| CentralManager/FormCentralConnectionGroups.cs | OpenDental/UI/FolderBrowserDialog.cs | function call, inferred call |
| CentralManager/FormCentralConnections.Designer.cs | OpenDentBusiness/Remoting/Meth.cs | function call, inferred call |
| CentralManager/FormCentralConnections.Designer.cs | OpenDentBusiness/UI/GridOD.cs | function call, inferred call |
| CentralManager/FormCentralConnections.Designer.cs | OpenDental/Forms/FormSheetDefEdit.cs | function call, inferred call |
| CentralManager/FormCentralConnections.Designer.cs | OpenDental/UI/Button.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | CentralManager/FormCentralConnectionEdit.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | CentralManager/FormCentralConnections.Designer.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | OpenDentBusiness/Cache/PrefC.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | OpenDentBusiness/Data Interface/CentralConnections.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | OpenDentBusiness/Data Interface/ConnectionGroups.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | OpenDentBusiness/Data Interface/Lans.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | OpenDentBusiness/Data Interface/Prefs.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | OpenDental/UI/FolderBrowserDialog.cs | function call, inferred call |
| CentralManager/FormCentralConnections.cs | RdlEngine/Definition/Rows.cs | function call, inferred call |
| CentralManager/FormCentralGroupPermEdit.Designer.cs | OpenDental/Forms/FormSheetDefEdit.cs | function call, inferred call |
| CentralManager/FormCentralGroupPermEdit.Designer.cs | OpenDental/UI/Button.cs | function call, inferred call |
| CentralManager/FormCentralGroupPermEdit.cs | CentralManager/FormCentralGroupPermEdit.Designer.cs | function call, inferred call |
| CentralManager/FormCentralGroupPermEdit.cs | OpenDentBusiness/Data Interface/GroupPermissions.cs | function call, inferred call |

## core_files
Evidence: file graph degree count only.
| File | Total degree | In-degree | Out-degree |
| --- | --- | --- | --- |
| OpenDentBusiness/Remoting/Meth.cs | 1507 | 1502 | 5 |
| CodeBase/Utilities/ODPrimitiveExtensions.cs | 1181 | 1174 | 7 |
| OpenDental/UI/Button.cs | 1143 | 1139 | 4 |
| OpenDental/Forms/FormSheetDefEdit.cs | 1074 | 1014 | 60 |
| OpenDental/Logic/Lan.cs | 1019 | 1017 | 2 |
| OpenDental/UI/BordersDpi/FormODBase.cs | 1013 | 993 | 20 |
| OpenDentBusiness/Db/Db.cs | 870 | 857 | 13 |
| OpenDental/UI/MsgBox.cs | 795 | 793 | 2 |
| CodeBase/Utilities/ODThread.cs | 793 | 787 | 6 |
| OpenDental/UI/FolderBrowserDialog.cs | 701 | 699 | 2 |
| OpenDentBusiness/UI/GridOD.cs | 668 | 648 | 20 |
| OpenDentBusiness/Cache/PrefC.cs | 649 | 638 | 11 |
| OpenDentBusiness/Data Interface/Prefs.cs | 621 | 610 | 11 |
| RdlEngine/Functions/VBFunctions.cs | 469 | 468 | 1 |
| OpenDentBusiness/Data Interface/ReplicationServers.cs | 436 | 431 | 5 |
| OpenDentBusiness/Data Interface/Patients.cs | 403 | 343 | 60 |
| OpenDental/UI/ListBoxOD.cs | 384 | 379 | 5 |
| OpenDental/Main Modules/FormOpenDental.cs | 380 | 42 | 338 |
| OpenDentBusiness/Data Interface/Lans.cs | 311 | 303 | 8 |
| OpenDentBusiness/Data Interface/Providers.cs | 294 | 274 | 20 |
| OpenDentBusiness/Data Interface/Defs.cs | 288 | 279 | 9 |
| CodeBase/Utilities/MiscUtils.cs | 286 | 281 | 5 |
| OpenDentBusiness/Data Interface/Clinics.cs | 285 | 262 | 23 |
| OpenDental/Main Modules/ControlChart.cs | 280 | 70 | 210 |
| OpenDentBusiness/Db Multi Table/Security.cs | 259 | 247 | 12 |
| OpenDental/Misc/ClassesShared.cs | 259 | 250 | 9 |
| OpenDentBusiness/Data Interface/SecurityLogs.cs | 258 | 245 | 13 |
| OpenDentBusiness/Db/DbHelper.cs | 218 | 210 | 8 |
| OpenDentBusiness/Data Interface/Procedures.cs | 217 | 145 | 72 |
| CodeBase/Utilities/ODFileUtils.cs | 213 | 203 | 10 |

## database_writes
Evidence: actual source matches to `table/from/collection` write operations, plus caller count for the enclosing Python callgraph function when available. No name-only matching is used.
_No rows found from the available direct evidence._

## external_calls
Evidence: direct Python/JavaScript/TypeScript import detection, excluding stdlib and local top-level modules.
_No rows found from the available direct evidence._

## ui_interactions
Evidence: direct HTML/UI element extraction from the HTML UI graph artifact.
_No rows found from the available direct evidence._

## known_todos
Evidence: literal TODO/FIXME-style comment extraction from repo comments.
| File | Line | Tag | Text |
| --- | --- | --- | --- |
| CentralManager/FormCentralManager.cs | 254 | TODO | this shouldn't be necessary, and I'm wondering if there are other caches that need to be refreshed. |
| CentralManager/FormCentralManager.cs | 668 | TODO | FillGrid will be triggered if any windowInfo changes. |
| CentralManager/FormCentralManager.cs | 1085 | TODO | this might be a bad test for a window being gone |
| CentralManager/NativeMethods.cs | 83 | TODO | could be invalid retVal.Add(hChildWnd); } return retVal; //not any shorter than GetChildWindows } |
| CodeBase/Utilities/MsgBoxCopyPaste.cs | 139 | TODO | Implement ODprintout pattern |
| CodeBase/Utilities/ODEnvironment.cs | 153 | XXX | .XXX.XXX).  Catches failure in parsing. |
| Direct2dWrapper/D2DWrapperHwnd.cpp | 263 | TODO | test to see if the device becomes unavailable. |
| Direct2dWrapper/D2DWrapperHwnd.cpp | 322 | TODO | What does this do on a 4K monitor |
| JobManagerDashboard/MainWindow.xaml.cs | 60 | TODO | Template this in xaml and pass in the object for the template to autogen, save for after initial working commit. |
| JobManagerDashboard/MainWindow.xaml.cs | 110 | TODO | Call the today click here, however this will require waiting for the UI to draw first otherwise the height value we animate to is 0. |
| JobManagerDashboard/MainWindow.xaml.cs | 373 | TODO | put this in its own model class |
| JobManagerDashboard/MainWindow.xaml.cs | 384 | TODO | put this in its own model class |
| MobileWeb/scripts/jqtouch.js | 542 | TODO | insert dirty joke) |
| MobileWeb/scripts/jqtouch.js | 566 | TODO | Try with all click events (no tap) |
| MobileWeb/scripts/jqueryui/jquery.ui.core.js | 288 | TODO | determine which cases actually cause this to happen |
| MobileWeb/scripts/jqueryui/jquery.ui.datepicker.js | 123 | TODO | rename to "widget" when switching to widget factory |
| OpenDental/Bridges/DentalStudio.cs | 36 | TODO | Dental Studio might need to be contacted or our bridge might need to be enhanced for sending / updating password hashes. |
| OpenDental/Bridges/PandaPerio.cs | 129 | XXX | )XXX-XXXX to XXX-XXX-XXXX |
| OpenDental/Forms/FormAllergyDefEdit.cs | 40 | TODO | Implement similar code for Unii |
| OpenDental/Forms/FormAllergyDefEdit.cs | 55 | TODO | Implement this |
| OpenDental/Forms/FormAllergyDefEdit.cs | 91 | TODO | Do UNII check once the table is added |
| OpenDental/Forms/FormApptEdit.cs | 1795 | TODO | ? Consider changing PatternSecondary length to match Pattern length.  But there are many places in the program where this would need to be done.  Probably easier to assume they can be out of synch. |
| OpenDental/Forms/FormBilling.cs | 501 | TODO | Query the database to get an updated list of unsent bills and compare them to the local list to make sure that we do not resend statements that have already been sent by another user. |
| OpenDental/Forms/FormCDSSetup.cs | 154 | TODO | Later. No time now for group level permission editing. |
| OpenDental/Forms/FormCDSSetup.cs | 163 | TODO | instead of updating all permissions. Update only the permissions neccesary. |
| OpenDental/Forms/FormCdsTriggerEdit.cs | 474 | TODO | TODO: |
| OpenDental/Forms/FormClaimPrint.cs | 117 | TODO | Implement ODprintout pattern - print or debug preview control |
| OpenDental/Forms/FormClaimPrint.cs | 693 | XXX | )XXX-XXXX |
| OpenDental/Forms/FormClaimPrint.cs | 899 | XXX | )XXX-XXXX |
| OpenDental/Forms/FormClaimPrint.cs | 4557 | TODO | Find a better place to put this method. |
| OpenDental/Forms/FormClaimPrint.cs | 4574 | TODO | Find a better place to put this method. |
| OpenDental/Forms/FormClearinghouseEdit.cs | 476 | TODO | Check all parts of program to allow either trailing slash or not |
| OpenDental/Forms/FormCloudManagement.cs | 28 | TODO | Fetch the maximum storage size and display (leave this for a future job) |
| OpenDental/Forms/FormCodeSystemsImport.cs | 903 | TODO | include more user information |
| OpenDental/Forms/FormCpts.cs | 101 | TODO | Either change to adding a snomed code instead of an ICD9 or don't allow users to add SNOMED codes other than importing. changed=true; Snomed snomed=new Snomed(); FormSnomedEdit FormI=new FormSnomedEdit(snomed); FormI.IsNew=true; FormI.ShowD |
| OpenDental/Forms/FormCreditCardEdit.cs | 710 | TODO | Open form to have user enter the CC number.  Then make API call to update cc instead of wiping out token. |
| OpenDental/Forms/FormDatabaseMaintenancePat.cs | 214 | TODO | Make sure that DBM methods with break downs ALWAYS have the break down in the fix section. |
| OpenDental/Forms/FormEcwDiag.cs | 272 | TODO | if(false) {//segmentFields[9]!="{???}") { //Don't know what this should look like when properly configured. TODO |
| OpenDental/Forms/FormEcwDiag.cs | 277 | TODO | if(false) {//segmentFields[10]!="{???}") { //Don't know what this should look like when properly configured. TODO |
| OpenDental/Forms/FormEcwDiag.cs | 375 | TODO | Need example of a valid DFT message to validate this segment. continue; case "ZX1": //TODO: Need example of a valid DFT message to validate this segment. continue; default: continue; } } //Validate existance of segments if(!segmentsContaine |
| OpenDental/Forms/FormEcwDiag.cs | 478 | TODO | maybe add some more specific details here."); |
| OpenDental/Forms/FormEHR.cs | 134 | TODO | ProvPat may not be the primary provider in the future. |
| OpenDental/Forms/FormEhrClinicalSummary.cs | 112 | TODO | It would be more patient friendly if we instead generated a PDF file containing the Clinical Summary printout, or if we simply displayed the Clinical Summary in the portal. |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 56 | TODO | hide the rest of the controls that shouldn't show if importing or view only. |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 268 | TODO | seperate notes for labs and results.</summary> |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 303 | TODO | Make this neater. Will display extra spaces if missing prefix suffix or middle names. |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 454 | TODO | validate the controls |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 543 | TODO | UI and this value. |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 575 | TODO | UI and Save |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 588 | TODO | parent result. |
| OpenDental/Forms/FormEhrLabOrderEdit2014.cs | 609 | TODO | this |
| OpenDental/Forms/FormEhrLabOrderImport.cs | 140 | TODO | maybe add more code here for when we come back from form... In case we delete a lab from the form. |
| OpenDental/Forms/FormEhrLabOrders.cs | 86 | TODO | Import external OIDs and PatIDs so that we can identify this patient next time. |
| OpenDental/Forms/FormEhrLabOrders.cs | 112 | TODO | The code above works, but ignores more recent lab results. Although the lab order my be unchanged there may be updated lab results. |
| OpenDental/Forms/FormEhrLabOrders.cs | 170 | TODO | maybe add more code here for when we come back from form... In case we delete a lab from the form. |
| OpenDental/Forms/FormEhrLabResultEdit2014.cs | 307 | TODO | validate the controls |
| OpenDental/Forms/FormEhrLabResultEdit2014.cs | 468 | TODO | Actually delete lab result? |
| OpenDental/Forms/FormEhrSetup.cs | 215 | TODO | include more user information |
| OpenDental/Forms/FormEligibilityResponseDisplay.cs | 177 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormEncounterEdit.cs | 158 | TODO | valid date box, validation here. |
| OpenDental/Forms/FormEServicesEClipboard.cs | 310 | TODO | Validate ByodSmsTempalte has [ByodUrl] |
| OpenDental/Forms/FormFeeSchedTools.cs | 1035 | TODO | js Why? |
| OpenDental/Forms/FormHelpBrowser.cs | 29 | XXX | " (205,194,etc).</summary> |
| OpenDental/Forms/FormIcd10s.cs | 101 | TODO | Either change to adding a snomed code instead of an ICD9 or don't allow users to add SNOMED codes other than importing. changed=true; Snomed snomed=new Snomed(); FormSnomedEdit FormI=new FormSnomedEdit(snomed); FormI.IsNew=true; FormI.ShowD |
| OpenDental/Forms/FormInfobutton.cs | 530 | TODO | "); |
| OpenDental/Forms/FormInfobutton.cs | 533 | TODO | "); |
| OpenDental/Forms/FormInfobutton.cs | 551 | TODO | SNOMED CT Problem Code."); |
| OpenDental/Forms/FormInfobutton.cs | 554 | TODO | SNOMED CT Problem Name"); |
| OpenDental/Forms/FormInfobutton.cs | 557 | TODO | SNOMED CT Medication Code."); |
| OpenDental/Forms/FormInfobutton.cs | 560 | TODO | SNOMED CT Medication Name."); |
| OpenDental/Forms/FormInfobutton.cs | 563 | TODO | SNOMED CT Lab Results Code??"); |
| OpenDental/Forms/FormInfobutton.cs | 566 | TODO | SNOMED CT Lab Results Name??"); |
| OpenDental/Forms/FormInfobutton.cs | 570 | TODO | "); |
| OpenDental/Forms/FormInfobutton.cs | 573 | TODO | "); |
| OpenDental/Forms/FormInfobutton.cs | 1353 | TODO | Implement more fields, this is just |
| OpenDental/Forms/FormInfobutton.cs | 1402 | TODO | later, maybe |
| OpenDental/Forms/FormInsPlan.cs | 1899 | TODO | Remove after Canadian claim certification is complete. |
| OpenDental/Forms/FormInsPlan.cs | 2068 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormLetterMerges.cs | 240 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormMassEmailList.cs | 300 | TODO | Might want to check user preferences or permissions |
| OpenDental/Forms/FormMassEmailList.cs | 317 | TODO | , change from ternary |
| OpenDental/Forms/FormMassEmailList.cs | 322 | TODO | , if All selected, use 0; |
| OpenDental/Forms/FormMessageReplacements.cs | 218 | TODO | mimic pattern in Recalls.GetAddrTable |
| OpenDental/Forms/FormMessageReplacements.cs | 226 | TODO | these replacements are a lot of work. |
| OpenDental/Forms/FormODSnippingTool.cs | 66 | HACK | to make the snipped image look centered if it is smaller than the forms default size. |
| OpenDental/Forms/FormOrthoChart.cs | 889 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormPatFieldDefEdit.cs | 58 | TODO | check existing values to make sure that it makes sense to change the type.  Especially when moving to currency or date. |
| OpenDental/Forms/FormPatientSelect.cs | 241 | XXX | )xxx-xxxx |
| OpenDental/Forms/FormPayment.cs | 2444 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Forms/FormPayPlan.cs | 309 | TODO | Create a helper class within PayPlanL called PayPlanRow? that will give us structure for adding to the grid and sorting. |
| OpenDental/Forms/FormPayPlanChargeEdit.cs | 113 | TODO | test dates?  The day of the month should be the same as all others |
| OpenDental/Forms/FormPaySimple.cs | 472 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Forms/FormPrepaymentTool.cs | 59 | TODO | see if this can be removed, currently is only set and never referenced. |
| OpenDental/Forms/FormPrntScrn.cs | 101 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormProcButtonQuickEdit.cs | 65 | TODO | Validation, if we need any. |
| OpenDental/Forms/FormProcCodes2.cs | 1229 | TODO | overload to show generic picker for feeschedgroups. |
| OpenDental/Forms/FormProcGroup.cs | 663 | TODO | Print a note about Exam Sheet added. |
| OpenDental/Forms/FormProgramLinkEdit.cs | 189 | TODO | change this logic to be explicit instead of implicit (i.e get a list of all controls we want to explicitly disable.) |
| OpenDental/Forms/FormRecallList.cs | 1079 | TODO | process return messages. Update commlog and change recall statuses for postcards that were sent. |
| OpenDental/Forms/FormRecallList.cs | 1919 | TODO | in the future, use this to replace the need to use _tableRecalls in this form.</summary> |
| OpenDental/Forms/FormReconcileAllergy.cs | 185 | TODO | Change to UNII |
| OpenDental/Forms/FormReconcileAllergy.cs | 371 | TODO | Change to UNII |
| OpenDental/Forms/FormReconcileAllergy.cs | 485 | TODO | Change to UNII |
| OpenDental/Forms/FormReconcileAllergy.cs | 519 | TODO | Change to UNII |
| OpenDental/Forms/FormReconcileAllergy.cs | 529 | TODO | Make an allergy measure event if one is needed for MU3. |
| OpenDental/Forms/FormReconcileEdit.cs | 234 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Forms/FormReferralProcTrack.cs | 48 | TODO | checkbox |
| OpenDental/Forms/FormReportsUds.cs | 59 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormSheetFillEdit.cs | 1773 | TODO | test this |
| OpenDental/Forms/FormSupplies.cs | 353 | TODO | fix gaps caused by hidden supplies |
| OpenDental/Forms/FormTimeCardRuleEdit.cs | 174 | TODO | Ask Cameron if it is ok to make time card rules that affect all clinics. |
| OpenDental/Forms/FormTPsign.cs | 287 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Forms/FormTPsign.cs | 472 | TODO | Implement ODprintout pattern |
| OpenDental/Forms/FormWikiListItemEdit.cs | 58 | HACK | together the location to put the combo box |
| OpenDental/Forms/FormWikiRename.cs | 26 | TODO | later:replace this with a dynamic "Home" pagename lookup like: PrefC.GetString(PrefName.WikiHomePage); |
| OpenDental/Forms Reports/FormQuery.cs | 856 | TODO | Implement ODprintout pattern - print or debug preview control |
| OpenDental/Forms Reports/FormRpStatement.cs | 249 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Forms Reports/FormSearchPatNotes.cs | 32 | TODO | Add any constructor code after InitializeComponent call |
| OpenDental/Forms Reports/ReportSimpleGrid.cs | 32 | HACK | to allow printing account numbers on deposit slips in a different font.  It will typically be null.  It will be gone soon.</summary> |
| OpenDental/InternalTools/Job Manager/FormJobAdd.cs | 170 | TODO | add status of FR. Difficult because FR dataset comes from webservice. |
| OpenDental/InternalTools/Job Manager/FormJobAdd.cs | 178 | TODO | add status of FR. Difficult because FR dataset comes from webservice. |
| OpenDental/InternalTools/Job Manager/FormJobLinks.cs | 108 | TODO | case JobLinkType.Quote://TODO |
| OpenDental/InternalTools/Job Manager/FormJobManager.cs | 2274 | TODO | Add this back in later |
| OpenDental/InternalTools/Job Manager/FormJobManager.cs | 2578 | TODO | Change this to be more legible |
| OpenDental/InternalTools/Job Manager/FormJobManagerOverview.cs | 123 | TODO | OwnerNum is not a good enough check here. |
| OpenDental/InternalTools/Job Manager/FormJobManagerOverview.cs | 259 | TODO | Centralize a save method so job saving can be called from anywhere and perform the same functionality |
| OpenDental/InternalTools/Job Manager/FormJobManagerOverview.cs | 498 | TODO | Make this work -- maybe add a dateimplemented column |
| OpenDental/InternalTools/Job Manager/UserControlJobEdit.cs | 701 | TODO | add status of FR. Difficult because FR dataset comes from webservice. |
| OpenDental/InternalTools/Job Manager/UserControlJobEdit.cs | 708 | TODO | add status of FR. Difficult because FR dataset comes from webservice. |
| OpenDental/InternalTools/Job Manager/UserControlJobEdit.cs | 4102 | TODO | fix this to get rid of orphaned links when FRs are deleted. |
| OpenDental/InternalTools/Phones/FormMapHQ.cs | 324 | TODO | replace image with one from Nathan |
| OpenDental/InternalTools/Phones/PhoneTile.cs | 149 | TODO | replace image with one from Nathan |
| OpenDental/Logic/ClaimL.cs | 552 | TODO | Wording. |
| OpenDental/Logic/EtransL.cs | 251 | TODO | Will the negative writeoff be cleared back to zero anywhere else (ex ClaimProc edit window)? |
| OpenDental/Main Modules/ControlAppt.cs | 3038 | TODO | small bug here. When first run, VerifyIns won't show because view not loaded yet. Solution: Jordan will rework RefreshModuleDataPeriod |
| OpenDental/Main Modules/ControlAppt.cs | 4653 | TODO | todo: |
| OpenDental/Main Modules/ControlChart.cs | 7840 | TODO | if proc Date is within show date range; return true; |
| OpenDental/Main Modules/ControlChart.cs | 7953 | TODO | track down where this is altered.  Optimize for eCW: |
| OpenDental/Main Modules/ControlChart.cs | 7962 | TODO | might change for planned appt: |
| OpenDental/Main Modules/ControlChart.cs | 7964 | TODO | refresh as needed elsewhere: |
| OpenDental/Main Modules/ControlChart.cs | 7966 | TODO | optimize for Full mode: |
| OpenDental/Main Modules/ControlChart.cs | 8779 | TODO | compare with: Bridges.ECW.AptNum, no need to generate PDF segment, pdfs only with eCW and this button not available with eCW integration |
| OpenDental/Main Modules/ControlChart.cs | 10737 | TODO | //TODO: |
| OpenDental/Main Modules/ControlImages.cs | 170 | TODO | In the future use a device locator in the xImagingDeviceManager |
| OpenDental/Main Modules/ControlImages.cs | 2262 | TODO | Implement ODprintout pattern |
| OpenDental/Main Modules/ControlImagesJ.cs | 3623 | TODO | if(treeMain.SelectedNode!=null) { treeMain.SelectedNode.EnsureVisible(); } |
| OpenDental/Main Modules/ControlImagesJ.cs | 4640 | TODO | Todo: |
| OpenDental/Main Modules/ControlImagesJ.cs | 4655 | TODO | Todo: |
| OpenDental/Main Modules/ControlTreat.cs | 2204 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Main Modules/ControlTreat.cs | 3757 | TODO | Implement ODprintout pattern - MigraDoc |
| OpenDental/Main Modules/ControlTreat.cs | 3818 | TODO | test this |
| OpenDental/Main Modules/FormOpenDental.cs | 83 | TODO | look into this dict of dicts.</summary> |
| OpenDental/Main Modules/FormOpenDental.cs | 894 | TODO | Need to differentiate between normal resizing handled by LayoutManager |
| OpenDental/Main Modules/FormOpenDental.cs | 1107 | HACK | but the customer is very large and needs this change ASAP.  Nathan has suggested that we create a ticket with eCW to complain about this and make them fix it. |
| OpenDental/Main Modules/FormOpenDental.cs | 1203 | TODO | decide action |
| OpenDental/Main Modules/FormOpenDental.cs | 1219 | TODO | decide action |
| OpenDental/Main Modules/FormOpenDental.cs | 1588 | TODO | If there are still issues with TP refreshing, include TP prefs in needsRedraw() |
| OpenDental/Misc/Pop3.cs | 1 | XXX | .com", "yyy", "zzz"); ArrayList list = obj.List(); foreach (Pop3Message msg in list ){ Pop3Message msg2 = obj.Retrieve(msg); System.Console.WriteLine("Message {0}: {1}", msg2.number, msg2.message); } obj.Disconnect(); } catch(Pop3Exception  |
| OpenDental/ReportingForRdl/FormReportCustom.cs | 251 | TODO | Implement ODprintout pattern |
| OpenDental/ReportingForRdl/FormReportForRdl.cs | 252 | TODO | Implement ODprintout pattern |
| OpenDental/ReportingForRdl/Allocators/MyAllocator1/SupportingCode/PP_LedgerItem.cs | 347 | XXX | ,yyyy; xxxx2, yyyy2; xxx3,yyyy3 |
| OpenDental/ReportingForRdl/Allocators/MyAllocator1/SupportingCode/PP_LedgerItem.cs | 348 | XXX | is the LedgerItemNumber and yyyy is the amount alocated from this |
| OpenDental/ReportingForRdl/Allocators/MyAllocator1/SupportingCode/PP_LedgerItem.cs | 479 | XXX | ,yyyy /// xxx= provider num /// yyyy = amount /// Throws exception if 'this' is not a payment or writeoff type. /// </summary> /// <param name="Parameters"></param> /// <returns></returns> public PP_LedgerItem[] SplitPaymentWriteOffItem(str |
| OpenDental/SheetFramework/SheetEditMobileCtrl.cs | 1350 | HACK | prevents that.</summary> |
| OpenDental/UI/Button.cs | 271 | TODO | this is broken for LayoutManager, but only noticed for foreign language and is rare |
| OpenDental/UI/Button.cs | 404 | HACK | for Direct2d to match up that gradient with the DirectX one. |
| OpenDental/UI/ToolBarOD.cs | 450 | HACK | for Direct2d to match up that gradient with the DirectX one. |
| OpenDental/UI/BordersDpi/LayoutManagerForms.cs | 677 | HACK | ; it scales nicely. |
| OpenDental/UI/ClinicSelector/FormComboPicker.cs | 405 | TODO | (low priority) |
| OpenDental/UI/Direct2d/Direct2d.cs | 147 | TODO | Atlas effect to pack multiple icons or thumbnails into a single image. |
| OpenDental/UI/ImagesModule/ImageSelector.cs | 398 | TODO | ID2D1RenderTarget::DrawTextLayout to center text float widthStr=g.MeasureString(str,Font).Width; d.DrawText(Color.Black, x:1+LayoutManager.Scale(78)/2-widthStr/2+3, y:2.5f+LayoutManager.Scale(3), width:widthStr+10, height:Font.Height, fontS |
| OpenDental/UI/ImagesModule/ImageSelector.cs | 754 | TODO | fire an event that will tell ControlImages to save the entire mount to a tempfile of name that we pass |
| OpenDental/UI/ImagesModule/ImageSelector.cs | 976 | TODO | replace |
| OpenDental/UI/ImagesModule/ImageSelectorTemp.cs | 720 | TODO | fire an event that will tell ControlImages to save the entire mount to a tempfile of name that we pass |
| OpenDental/UI/VideoCamera/CameraMethods.cs | 84 | TODO | fix exception |
| OpenDental/UI/VideoCamera/CameraMethods.cs | 125 | TODO | make a better exception |
| OpenDental/User Controls/ContrPerio.cs | 1386 | TODO | (some day): loop through each individually and only invalidate small area. |
| OpenDental/User Controls/EmailPreviewControl.cs | 18 | TODO | Replace this flag with a new flag on the email address object.</summary> |
| OpenDental/User Controls/MapAreaPanel.cs | 347 | TODO | removed scrolling for now. It was causing more problems than it was worth. |
| OpenDentBusiness/Data Interface/AllergyDefs.cs | 167 | TODO | hide snomed code from foreign users |
| OpenDentBusiness/Data Interface/Appointments.cs | 4230 | XXX | It is now acceptable to have no hyg time at the beginning or at the ending of the appointment.  E.g. X + XX = XXX |
| OpenDentBusiness/Data Interface/Appointments.cs | 4233 | XXX | / + /X/ = //XXXX/ |
| OpenDentBusiness/Data Interface/Appointments.cs | 4254 | XXX | ///XX///" should retain "XXX///XX" for the provider time portion. |
| OpenDentBusiness/Data Interface/CDSPermissions.cs | 10 | TODO | implement caching; |
| OpenDentBusiness/Data Interface/ClaimProcs.cs | 815 | TODO | Use new CRUD function to prevent issue with IN statement when using Oracle.  Derek will provide function. |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 15 | TODO | implement this patient select function if needed. |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 301 | TODO | No SetIDNTE? |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 418 | TODO | may need additional formatting/testing |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 500 | TODO | ? check to see if either triplet contained a valid code. |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 533 | TODO | ? check to see if either triplet contained a valid code. |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 566 | TODO | Message has been processed into an EHR Lab... Now we can do other things if we want to... |
| OpenDentBusiness/Data Interface/EhrLabs.cs | 774 | TODO | Finish this with Travis' Stuff |
| OpenDentBusiness/Data Interface/EhrMeasures.cs | 786 | TODO | Combine these queries to get old and new lab data |
| OpenDentBusiness/Data Interface/EhrMeasures.cs | 2665 | TODO | Order the measures nicely for Oracle users. |
| OpenDentBusiness/Data Interface/EhrMeasures.cs | 4282 | TODO | Order the measures nicely for Oracle users. |
| OpenDentBusiness/Data Interface/EhrMeasures.cs | 5165 | TODO | Order the measures nicely for Oracle users. |
| OpenDentBusiness/Data Interface/EhrTriggers.cs | 244 | TODO | TriggerObjectMessage |
| OpenDentBusiness/Data Interface/EhrTriggers.cs | 250 | TODO | TriggerObjectMessage |
| OpenDentBusiness/Data Interface/EhrTriggers.cs | 256 | TODO | TriggerObjectMessage |
| OpenDentBusiness/Data Interface/EhrTriggers.cs | 280 | TODO | TriggerObjectMessage |

## recently_changed
Evidence: local `git log` when a `.git` directory is available; otherwise concrete GitHub commit payload from analysis if present.
| Commit | Date | Subject | Files |
| --- | --- | --- | --- |
| 13c335c47e | 2022-02-24 10:45:33 -0800 | version 21.1.63.0 | BUILDING.Linux, CentralManager/Db/CentralConfigHelper.cs, CentralManager/Db/CentralConnectionHelper.cs, CentralManager/Db/CentralGroupPermissions.cs, CentralManager/Db/CentralSyncHelper.cs, CentralManager/Db/CentralUserGroups.cs, CentralManager/Db/CentralUserods.cs, CentralManager/FormCentralChooseDatabase.cs ... |
| b1170b2b40 | 2022-01-12 11:04:58 -0800 | README - Removed duplicate horizontal lines from underneath headers. | README.md |
| 3dc988b366 | 2022-01-12 11:00:59 -0800 | Initial README | README.md |
| 7f98bcace2 | 2022-01-07 10:14:14 -0800 | Initial commit | LICENSE, README.md |

## high_churn_files
Evidence: file occurrence/change count from local git history when available; otherwise concrete GitHub changed-file payload from analysis if present.
| File | Commit touch/change count |
| --- | --- |
| README.md | 3 |
| BUILDING.Linux | 1 |
| CentralManager/Db/CentralConfigHelper.cs | 1 |
| CentralManager/Db/CentralConnectionHelper.cs | 1 |
| CentralManager/Db/CentralGroupPermissions.cs | 1 |
| CentralManager/Db/CentralSyncHelper.cs | 1 |
| CentralManager/Db/CentralUserGroups.cs | 1 |
| CentralManager/Db/CentralUserods.cs | 1 |
| CentralManager/FormCentralChooseDatabase.cs | 1 |
| CentralManager/FormCentralChooseDatabase.resx | 1 |
| CentralManager/FormCentralConnectionEdit.cs | 1 |
| CentralManager/FormCentralConnectionEdit.designer.cs | 1 |
| CentralManager/FormCentralConnectionEdit.resx | 1 |
| CentralManager/FormCentralConnectionGroupEdit.Designer.cs | 1 |
| CentralManager/FormCentralConnectionGroupEdit.cs | 1 |
| CentralManager/FormCentralConnectionGroupEdit.resx | 1 |
| CentralManager/FormCentralConnectionGroups.Designer.cs | 1 |
| CentralManager/FormCentralConnectionGroups.cs | 1 |
| CentralManager/FormCentralConnectionGroups.resx | 1 |
| CentralManager/FormCentralConnections.Designer.cs | 1 |
| CentralManager/FormCentralConnections.cs | 1 |
| CentralManager/FormCentralConnections.resx | 1 |
| CentralManager/FormCentralGroupPermEdit.Designer.cs | 1 |
| CentralManager/FormCentralGroupPermEdit.cs | 1 |
| CentralManager/FormCentralGroupPermEdit.resx | 1 |
| CentralManager/FormCentralLogOn.cs | 1 |
| CentralManager/FormCentralLogOn.resx | 1 |
| CentralManager/FormCentralManager.Designer.cs | 1 |
| CentralManager/FormCentralManager.cs | 1 |
| CentralManager/FormCentralManager.resx | 1 |
| CentralManager/FormCentralPasswordChange.cs | 1 |
| CentralManager/FormCentralPasswordChange.designer.cs | 1 |
| CentralManager/FormCentralPasswordChange.resx | 1 |
| CentralManager/FormCentralPasswordCheck.cs | 1 |
| CentralManager/FormCentralPasswordCheck.designer.cs | 1 |
| CentralManager/FormCentralPasswordCheck.resx | 1 |
| CentralManager/FormCentralPatientSearch.Designer.cs | 1 |
| CentralManager/FormCentralPatientSearch.cs | 1 |
| CentralManager/FormCentralPatientSearch.resx | 1 |
| CentralManager/FormCentralPatientTransfer.Designer.cs | 1 |

## stable_files
Evidence: tracked files with zero touches in the latest 100 local git commits. Empty when no local `.git` evidence is available.
_No rows found from the available direct evidence._

## codemd_agent_guidance
Testing responsibilities and agent behavior are defined in `.codemd/agent_policy/testing.md`.
When using CODEMD MCP testing tools, follow the task-specific agent guidance returned by those tools.
