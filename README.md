I am an open-source software engineer and build backend systems and the infrastructure around them, primarily in Java, Go and Rust. My work has centred on event-driven systems, change data capture, databases, cloud native tools and the tooling needed to deploy and operate distributed workloads.I contribute to established open-source projects, where the work often involves understanding an existing codebase, tracing behaviour across components, and making changes that fit the project's architecture. My recent work includes host-based deployment for the Debezium Platform, fixes in Debezium Core, and a mobile-responsive implementation for MIT App Inventor.

## Open-source work

**Debezium / Red Hat | [Google Summer of Code 2026](https://summerofcode.withgoogle.com/programs/2026/projects/1xyxocte)**

Designed and implemented a host-based deployment path for the [Debezium Platform](https://github.com/debezium/debezium-platform), extending deployment beyond Kubernetes to remote Linux hosts, virtual machines, and bare-metal servers. The implementation covers SSH configuration parsing and host discovery, filesystem watching and reconciliation, Ansible-based provisioning, a standalone Quarkus Host Agent, pipeline lifecycle operations, status monitoring, configuration drift detection, and concurrency-safe host allocation.
[Host-based deployment: final report and architecture](https://github.com/debezium/debezium-design-documents/blob/main/gsoc/2026/d1vyanshu-kumar/final_submission.md), [Parent Tracker Issue](https://github.com/debezium/dbz/issues/2085)

Contributed fixes to connector behaviour and CDC access validation: [PostgreSQL: unchanged TOASTed JSONB values](https://github.com/debezium/debezium/pull/7168). Fixed an issue where unchanged TOASTed JSONB columns could appear as null in the after image.[SQL Server: CDC permission validation](https://github.com/debezium/debezium/pull/7132). Corrected validation when CDC is enabled at the database level but no tables are tracked yet.

**MIT App Inventor | Google Summer of Code 2025**

Worked on making the App Inventor authoring experience responsive on mobile devices, covering the Project Explorer, Designer, Blockly editor, navigation, and supporting UI components.
The implementation builds on the existing GWT and UiBinder architecture rather than relying on a CSS-only retrofit.
[Mobile-responsive implementation and review history](https://github.com/mit-cml/appinventor-sources/pull/3491), [Other merged App Inventor contributions](https://github.com/mit-cml/appinventor-sources/pulls?q=is%3Apr+author%3Ad1vyanshu-kumar+is%3Amerged)

[**Open Source Contribution Portfolio**](https://docs.google.com/document/d/1mP5n6P_U8J4taswqQXOP4xJ-wegROmPZDi5m2TqyFyw/edit?usp=sharing)

## Writing / Blogs
https://dev.to/d1vyanshukumar/ </br>
https://medium.com/@kumardivyanshu118

-----

<h3>❤️ My Inspiration</h3>
  <p>
    <em>“If someone betrays you once, it’s their fault; <br>
    if they betray you twice, it’s your fault.”</em>
  </p>
  <p><strong>― Eleanor Roosevelt</strong></p>
</br>

![Profile Views](https://komarev.com/ghpvc/?username=d1vyanshu-kumar&color=blue&style=flat-square)
</div>




  

<!---
d1vyanshu-kumar/d1vyanshu-kumar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
