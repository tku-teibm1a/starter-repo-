# Model Specification

> A **living document**. Revise it in place as your understanding changes — do not rewrite it from scratch.
> Its git history is read as well as its content. By Week 14 it becomes the opening section of your project proposal.
>
> Sections appear as the course reaches them. Delete this quote block once you start.

**Team:** *(number)* · **Last revised:** *(date)*

---

## 1. Timing model
*(Week 2. Which model do you assume — synchronous, asynchronous, something between? What evidence supports it? Revise in Week 3 with your measured skew, and again in Week 10 with your synchronised bound.)*

## 2. Failure model
*(Week 2. Crash-stop or crash-recovery? What state does a Pico lose on reset? What kinds of failure are you assuming are out of scope?)*

## 3. Failure detection
*(Week 2, expanded in Week 8. How would you decide a node has failed? What is the cost of deciding wrongly? Later: your heartbeat period, timeout, and what happens on suspicion and on revival.)*

## 4. Channel guarantees
*(Week 4. What does your transport actually promise — reliability, ordering? What did you measure rather than assume?)*

## 5. Architecture and dependencies
*(Week 5. Your broker is a primary. What depends on it, and what happens when it stops?)*

## 6. Conflicts and ordering
*(Week 6. Your node-to-index mapping, and your conflict-resolution policy.)*

## 7. Coordination
*(Week 9. Your election rule, your quorum size, and what your system does when no majority is reachable.)*

## 8. Time alignment
*(Week 10. Your measured ε, how you derived it, and your resynchronisation interval.)*

## 9. Computation placement
*(Week 11. Where each stage runs, and why. What happens when the preferred location is unreachable?)*

---

## Revision log
*(Optional but useful. One line per change: what you revised and what made you revise it.)*

| Week | Change |
|---|---|
| | |
