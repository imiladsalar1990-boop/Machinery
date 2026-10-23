Build a complete Android CMMS app named “ماشینری” (Mashinari) for an industrial machinery maintenance workshop. Use Persian (Farsi) RTL layout throughout and make it usable on Android phones.

Mandatory business rules:
- The incentive/karaneh module is based ONLY on numeric work points.
- No overtime module, no overtime fields, and no overtime calculations anywhere.
- Never calculate or display money amounts (no Rial/Toman fields).
- Only a Manager role can finally approve maintenance reports and points.
- The manager can define base points for each operation (example: complete pump assembly = 20 points; large pump disassembly = 20 points).
- For each approved work report, the manager can assign a numeric point value to each participating employee individually.
- Save reusable templates for repeated jobs, but preserve the historical points already approved if a template later changes.
- Reports must show each employee’s points by date range and totals.
- Keep an audit history for edits to approved records.

CMMS modules requested:
1. Equipment register with tag number, location, type, manufacturer/model/serial number, photos, manuals and maintenance history.
2. Daily maintenance reports with date/time, equipment, work description, workers, status, notes and attachments.
3. Work orders with priority, requester, assigned staff, status, planning, execution, testing and closure.
4. Employee management and role-based access.
5. Manager approval workflow.
6. Numeric incentive points and reusable job templates.
7. PDF and Excel exports with date, equipment and employee filters.
8. Preventive maintenance schedules and checklists.
9. Spare parts inventory, stock movements and low-stock alerts.
10. Pump test records: flow, head, suction/discharge pressure, power, speed and vibration.
11. Fault codes, root-cause analysis and corrective actions.
12. Dashboard with open/overdue work orders and maintenance KPIs.
13. Offline entry with safe synchronization when connectivity returns.
14. Secure authentication, backups and audit logs.

Deliver working source code, not just mockups. Build incrementally, test each feature, document how to create an APK, and do not add paid services without approval. Clearly distinguish implemented features from planned features. Do not claim cloud sync or security exists unless actually implemented and tested.
