---
id: everydaycase-api-install
title: Встановлення
sidebar_custom_props:
  icon: FaCog
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Встановлення

Модулі DonateCase API:
- `api` — головний модуль, який містить основні конструкції для взаємодії з DCEveryDayCase.

## Maven
```xml title="Maven"
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>

<dependency>
    <groupId>com.wairesd.dceverydaycase</groupId>
    <artifactId>api</artifactId>
    <version>2.2</version>
    <scope>provided</scope>
</dependency>
```

## Gradle
```gradle title="Gradle"
maven {
    name = "jitpack.io"
    url = "https://jitpack.io"
}

dependencies {
    compileOnly("com.wairesd.dceverydaycase:api:2.2")
}