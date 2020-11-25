# Endjin.MetaPackage.SpecFlow

> NOTE: This work was moved to https://github.com/corvus-dotnet/Corvus.Testing

This repo is responsible for publishing a meta package that encapsulates the SpecFlow dependencies used in our OSS test libraries, and allows us to manage those dependencies as a single entity.

When using Dependabot to manage our updates to our SpecFlow dependencies, we get a number of pull requests that are awkward to orchestrate in order to effect a successful upgrade.

This package consolidates those dependencies so we can use Dependabot to bump them as a single operation.
