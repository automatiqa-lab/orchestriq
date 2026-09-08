# Orchestriq

The kernel for agents that run real operations. Evals, approvals, earned autonomy and EU AI Act Article 50 transparency live in the runtime, so every module inherits them.

The kernel knows nothing about your domain: no schemas, no industry logic, no opinion about what a good answer looks like. What it knows is how to run an agent under supervision - typed actions, a tool registry that decides what a module may call, full transcripts, scorers, an eval gate, and an approval inbox where unattended runs park their requests. Autonomy is a ladder climbed per action type on measured accuracy, not a setting a module can switch on for itself.

Part of [Automatiqa Lab](https://www.automatiqa.io/orchestriq-core/) - open-source experiments where operations meet the algorithm.

## The shape

A supply chain data model that ties signals, decisions, policy, and trace together, with a heartbeat that keeps the loop alive and maturity levels that let autonomy grow only as fast as trust does. Signals come in, decisions go out, policy decides what is allowed, and every step leaves a record you can audit.

## Status

Work in progress, built in public. Project page: [automatiqa.io/orchestriq-core](https://www.automatiqa.io/orchestriq-core/).

## License

MIT.
