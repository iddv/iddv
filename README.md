# Agent Rules for Creating Durable Projects

1. **Start Simple, Plan for Complexity:** Begin with a cohesive implementation that solves the core problem before introducing distributed architecture.
2. **Design Clean Boundaries:** Establish clear interfaces between components from day one, even when implemented together.
3. **Minimal Viable Infrastructure:** Deploy only what's needed to support current functionality while enabling future expansion.
4. **Core Value First:** Focus on delivering essential features that provide immediate customer value before expanding scope.
5. **Data-Driven Evolution:** Use metrics and actual usage patterns to guide architectural changes rather than speculative optimization.
6. **Observable by Default:** Implement comprehensive logging and monitoring from the beginning to understand system behavior.
7. **Automation from Day One:** Set up deployment automation early, even for simple systems, to enable confident iteration.
8. **Test for Resilience:** Create tests that validate system behavior under various conditions, not just happy paths.
9. **Separation Ready:** Design components that can function independently when extracted in the future.
10. **Consistent Interfaces:** Establish standard patterns for how components communicate, making future changes more predictable.
11. **Progressive Enhancement:** Build systems that deliver basic functionality first, then enhance as resources allow.
12. **Embrace Feedback Loops:** Create mechanisms to quickly incorporate user feedback into development priorities.

> These principles focus on pragmatic implementation while maintaining a clear path to future scalability based on actual needs rather than anticipated complexity.
