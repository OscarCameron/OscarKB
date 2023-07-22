# Introduction

z/OS is an Operating System that runs on IBM Mainframes. Having worked on z/OS for 4 years, I have to say it is definitely one of the most difficult Operating Systems to wrap your head around. And this is not made any easier by the lack of online resources for learning about z/OS.

To quote IBM:
>IBM z/OS® is a operating system for IBM zSystems mainframes, suitable for continuous, high-volume operation with high security and stability.

## Who uses Mainframes?

Typically, organisations such as Banks & Building Societies :bank:, Airlines :airplane:, and Insurers :bar_chart: use Mainframes due to their suitability at processing _vast_ transactional workloads extremely efficiently. Even Tescos use Mainframes!

z/OS has a backwards-compatibility guarantee, meaning that applications written back in the 70s for [MVS](https://en.wikipedia.org/wiki/MVS#Evolution_of_MVS) will still run on z/OS 2.5, released in 2023 (and believe me - they do!).

## Workload Types

Workload on the Mainframe is typically categorised into two buckets: Batch, and Online. To keep analogous with a Bank, the process to update the ledger with your pending transactions would take place in batch. Conversely, you would retrieve your account balance via mobile banking using an online service.

## Aren't Mainframes Dead?

Well, ask a seasoned Mainframer and they'll tell you that claim has been bandited around for the last 40 years!

Cloud is typically seen as the future platform-of-choice for all business-critical workload, and with a dwindling hiring pool, there is a perception of a pressing need to migrate workload.

However, by my account, this is yet to have ever been successfully undertaken (by organisations with a large Mainframe footprint). There certainly are cases of Banks etc. undertaking 'modernisation' projects, but the promises made at the start of these projects (e.g. cost reductions, improved performance) are rarely realised.

However, it is certainly true that the Mainframe platform has issues: applications running on the Mainframe are often _extremely_ old. This isn't inherently bad (in fact, it shows how well architected they are - to still play a vital role in a world of Mobile Banking, having been developed at a time before email!), however, it is a massive undertaking to re-design these applications using modern languages and patterns. When people refer to "Mainframe Modernisation", I believe this is where efforts need to be focused.

The platform itself is capable of running all 'modern' workloads. Containerised Applications, Orchestration via OpenShift, and you can use whatever languages you like with official SDK support from IBM: Go, Java, Node.JS, Java - whatever you want! With the development of [Zowe](https://www.zowe.org), you can now interact with many parts of the z/OS environment via a CLI. This makes integration with a business' distributed environments straight forward.

