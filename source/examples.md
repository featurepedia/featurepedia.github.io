---
extends: _layouts.master
section: body
---

## examples

### todo tracking

#### Capability: Access across multiple devices

```
Capability: Access across multiple devices

As a todo tracker,
In order to record things todo whenever they occur to me,
I want to be able to view my todos on multiple devices
```

Solution: use a file format that is supported by apps on multiple
devices.

```
Feature: Todos can be edited on desktop
```


```
Feature: Todos can be edited on Android
```

----

#### Capability: Easy sync across multiple devices</h4>

```
Capability: Synchronisation across multiple devices

As a todo tracker,
In order to always have access to my latest list of things to do,
I want to have access to my todos on multiple devices
```

```
Feature: Automatic sync across multiple devices

As a todo tracker,
In order to always have access to my latest list of things to do,
I want to have my todos automatically sync between devices
```

<table>
    <thead>
        <tr>
            <th>Feature</th>
            <th>indieware</th>
            <th>todoist</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Todos can be edited on desktop</td>
            <td>emacs</td>
            <td>todoist</td>
        </tr>
        <tr>
            <td>Todos can be edited on Android</td>
            <td>orgzly</td>
            <td>todoist</td>
        </tr>
        <tr>
            <td>Todos can be edited on iPhone</td>
            <td>? - text editor</td>
            <td>todoist</td>
        </tr>
        <tr>
            <td>Automatic sync</td>
            <td>syncthing</td>
            <td>todoist</td>
        </tr>
    </tbody>
</table>
