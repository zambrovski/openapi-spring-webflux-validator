# Contributing

## Develop

#### 1. Fork it

#### 2. Build the project

```shell

mvn build

```

#### 3. Make a change

fix a bug, add a feature, update the doc, etc

#### 4. Run the Tests

```shell

mvn test

```

#### 5. Create a PR

## Misc

#### Add yourself as a contributor

After your PR has been merged, add yourself as a contributor.

To do sob, create a comment like the following on your PR:

@all-contributors please add @username for code and test!

Replace code with doc or test or infra or some combination depending on your contribution.

#### Package

Contributors are not responsible for pushing packages to mavencentral and jcenter. Contributors are responsible for validating that the package step succeeds.

```shell

mvn clean package dokka:javadocJar

```

