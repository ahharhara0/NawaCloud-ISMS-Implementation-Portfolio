# ISMS Scope and Context

## Organization
NawaCloud is a fictional 24-person software company providing a cloud appointment and booking platform for small clinics. The modeled service does not diagnose patients or store complete clinical records. Booking information may contain a person's name, contact details, appointment time, and clinic name, so it is treated as confidential in this scenario.

## Scope and boundaries
The scope covers the service lifecycle: product design, development, testing, deployment, application operations, technical support, and operational data. It also covers staff identities and managed endpoints, the cloud environment, code repositories, and third-party services that affect the service. Operations are remote; the modeled application and database run with one cloud provider.

Provider data centers and provider personnel, clinic devices and networks, medical records outside the platform, payment services not operated by NawaCloud, and personal home-office infrastructure are outside direct operational control. These boundaries do not remove supplier oversight or the duty to protect information handled by the service.

## Assumptions and dependencies
- The scenario excludes payment card data and complete medical records.
- Cloud hosting, email, identity, ticketing, and source hosting are critical dependencies.
- Only a small engineering group has privileged production access, making separation and review important.
- Illustrative recovery targets are RTO 8 hours and RPO 4 hours; a real organization would approve targets with customers.
- No jurisdiction-specific legal conclusion is assumed.

## Stakeholders
Clinic customers expect confidentiality, availability, and clear incident communication. Clinic users expect protected accounts and safe handling of booking data. Employees and contractors need clear responsibilities and practical procedures. Management needs risk visibility and resources. Suppliers need defined responsibilities and change coordination. Applicable regulators and contractual parties require obligations to be identified for the actual operating jurisdiction. The simulated auditor needs traceable evidence and independence from control owners.

## Illustrative objectives
1. Prevent unauthorized access to customer data and accounts.
2. Preserve booking and release integrity.
3. Target 99.5% monthly availability in the simulation.
4. Detect and escalate significant incidents within one hour of detection.
5. Test backup restoration quarterly.
6. Review risks, controls, and suppliers annually and after material change.

## Governance
The General Manager sponsors the ISMS and approves high residual-risk acceptance. The part-time Information Security Lead maintains the method and reporting. Product ownership approves service scope and requirements. The Engineering Lead owns development and platform security. The Operations Lead owns backups and monitoring. Administration supports workforce lifecycle and awareness. Asset owners maintain classification and access. The simulated auditor does not audit work they performed.

---

Prepared by **Ahmed Ban Harhara**  
[Ahmed.banharhara@gmail.com](mailto:Ahmed.banharhara@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/ahmed-ban-harhara-285a76264)

