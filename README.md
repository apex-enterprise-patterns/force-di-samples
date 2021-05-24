# Force DI Samples

The files in this project are various example implementations of the Force-DI Apex dependeny injection framework.

**Dependencies:** Must deploy [Force-DI](https://github.com/apex-enterprise-patterns/force-di) before deploying this library.

For more information on the Force-DI framework or dependency injection concepts, please refer to the [Force-DI](https://github.com/apex-enterprise-patterns/force-di) project.

Project Folders
---------------
The "core" framework is found in [Force-DI](https://github.com/apex-enterprise-patterns/force-di) project.  This includes the following:

| Folder | Description |
| ------ | ----------- |
| **force-di** | Core library, contains **Injector** Apex API and **<c:di_injector>** VF and Lightning Components |

The "samples" of how to use the framework can be found in this project.

| Folder | Description |
| ------ | ----------- |
| **force-app-1** | Sample application using the API and Components to inject Apex, VF and Lightning at runtime |
| **force-app-2** | Sample package providing impls for various bindings above |
| **force-app-3** | Sample package providing impls for various bindings above |
| **force-di-trigger-demo** | Sample basic trigger framework leveraging the API |


![Force DI Example](https://andrewfawcett.files.wordpress.com/2018/07/forcedi2.png)


