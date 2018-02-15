# Use Markdown Architectural Decision Records

We want to record architectural decisions made in this project.
Where do we store these records, and which structure should they follow?

## Considered Options

Location

* Wiki
* Tickets in Issue Tracker
* VCS

Structure

* [Michael Nygard's ADR template](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions) - Initial blueprint for "Architectural Decision Records"
* [MADR](https://adr.github.io/madr/) - Markdown Architectural Decision Records
* Other formats listed at <https://github.com/joelparkerhenderson/architecture_decision_record>

## Decision Outcome

Chosen option: VCS & MADR version 1.3.0, because
- All decisions should be stored as close to the code as possible.
- Implicit assumptions should be made explicit.
  Design documentation is important to enable people understanding the decisions later on.
  See also [A rational design process: How and why to fake it](https://doi.org/10.1109/TSE.1986.6312940).
- The MADR format is lean and fits our development style.
