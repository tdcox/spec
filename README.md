# ![CDEvents](cdevents_horizontal-color.png)

CDEvents is a common specification for Continuous Delivery events, enabling
interoperability in the complete software production ecosystem.

It's an incubated project at the
[Continuous Delivery Foundation](https://cd.foundation) (CDF).

## Background
<!--
Resources used for the background text
https://cd.foundation/blog/2021/03/16/cd-foundation-announces-industry-initiative-to-standardize-events-from-ci-cd-systems/
https://github.com/cdfoundation/toc/blob/master/sigs/sig-events.md
https://github.com/cdfoundation/sig-events
https://github.com/cdfoundation/toc/blob/master/proposals/cdevents/cdevents.md
-->
In a complex and fast moving CI/CD world with a lot of different tools and
platforms that need to communicate with each other interoperability stands as a
crucial thing. The maintainer of a CI/CD system needs to swap out tools in short
time with little to no stops.

The larger and more complex a CI/CD system becomes, challenges increase in
knowing how the tools communicate and what they do.

### What we provide

The CDEvents protocol defines a vocabulary of events enabling tools to
communicate in an interoperable way.

We extend other efforts such as CloudEvents by introducing purpose and semantics
to the event.

![stack](./images/stack.png)

By providing an interoperable way of tools to communicate we also provide means
to give an overview picture increasing observability, but also to give measuring
points for metrics.

## CDEvents Specification

The latest release of the specification on is
[v0.1.2](https://github.com/cdevents/spec/blob/v0.1.2/spec.md), and you can
continuously follow the latest updates of the specification on [the `main`
branch](./spec.md).

The concepts and ideas that have formed the current specification are outlined in the [CDEvents Primer](./primer/_index.md).
## CDEvents SDKs

CDEvents is developing as set of SDKs:

* [Go](https://github.com/cdevents/sdk-go)
* [Python](https://github.com/cdevents/sdk-python)
* [Java](https://github.com/cdevents/sdk-java)

## Community

### How to get involved

[Reach out](https://github.com/cdevents/community/blob/main/governance.md#project-communication-channels) to see what we're up
via:

* [slack](https://cdeliveryfdn.slack.com/archives/C030SKZ0F4K)
* [our mailing list](https://groups.google.com/g/cdevents-dev)
* [our working group meetings](https://calendar.google.com/event?action=TEMPLATE&tmeid=aWhyZjVwb3F2MnY2bml0anUyNDRvazdkdWpfMjAyMjAyMjJUMTYwMDAwWiBhbmRyZWEuZnJpdHRvbGlAbQ&tmsrc=andrea.frittoli%40gmail.com&scp=ALL)

### Contributing

If you would like to contribute, see our [contributing](https://github.com/cdevents/.github/blob/main/docs/CONTRIBUTING.md)
guidelines.

### Governance

The project has been started by the CDF
[SIG Events](https://github.com/cdfoundation/sig-events) and is currently
[governed](https://github.com/cdevents/community/blob/main/governance.md) by a few members of the SIG.
