# Getting Started with Kubernetes - Second Edition
This is the code repository for [Getting Started with Kubernetes - Second Edition](https://www.packtpub.com/virtualization-and-cloud/getting-started-kubernetes-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787283367), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Kubernetes has continued to grow and achieve broad adoption across various industries, helping you to orchestrate and automate container deployments on a massive scale.

This book will give you a complete understanding of Kubernetes and how to get a cluster up and running. You will develop an understanding of the installation and configuration process. The book will then focus on the core Kubernetes constructs such as pods, services, replica sets, replication controllers, and labels. You will also understand how cluster level networking is done in Kubernetes.

The book will also show you how to manage deployments and perform updates with minimal downtime. Additionally, you will learn about operational aspects of Kubernetes such as monitoring and logging. Advanced concepts such as container security and cluster federation will also be covered. Finally, you will learn about the wider Kubernetes ecosystem with OCP, CoreOS, and Tectonic and explore the third-party extensions and tools that can be used with Kubernetes.

By the end of the book, you will have a complete understanding of the Kubernetes platform and will start deploying applications on it.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
apiVersion: v1
kind: Pod
metadata:
 name: node-js-pod
spec:
 containers:
 - name: node-js-pod
 image: bitnami/apache:latest
 ports:
 - containerPort: 80
```

This book will cover downloading and running the Kubernetes project. You’ll need access to a Linux system (VirtualBox will work if you are on Windows) and some familiarity with the command shell.
Additionally, you should have a Google Cloud Platform account. You can sign up for a free trial here:

https://cloud.google.com/

Also, an AWS account is necessary for a few sections of the book. You can sign up for a free trial here:

https://aws.amazon.com/

## Related Products
* [Getting Started with Kubernetes](https://www.packtpub.com/virtualization-and-cloud/getting-started-kubernetes?utm_source=github&utm_medium=repository&utm_campaign=9781784394035)

* [Kubernetes Cookbook](https://www.packtpub.com/virtualization-and-cloud/kubernetes-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781785880063)

* [Mastering Kubernetes](https://www.packtpub.com/virtualization-and-cloud/mastering-kubernetes?utm_source=github&utm_medium=repository&utm_campaign=9781786461001)
