## Introduction
Modern businesses run on multiple applications and services. How well your business runs can often be impacted by how efficiently you can distribute the right data to the right task. Automating this flow of data can streamline your business even further. Choosing the right technology for these critical data integrations and process automation is also an important consideration.

Suppose you're a developer at a company that operates a bike rental system at a large state university. Your company recently acquired the rights to operate at another university in the next state.

The other university also has rental systems in place. You'll need to integrate with those existing systems too. The systems include bike tracking, inventory management, rental scheme registration, and more.

It's June and the university would like to have the rental system in place before students arrive on campus in late August. Your business runs on Azure and a requirement of this integration is that you don't take on any infrastructure maintenance or heavy upfront costs. As you expand into other universities, you need to be able to scale efficiently in order to keep costs down and your low margins viable.

## Identify the technology options
You don't have much time to get business processes properly integrated between your existing bike rental system and the system in use in the second campus. You'd like to make the most of your existing Azure expertise and you've read that Azure includes several different technologies that you can use to solve problems like this.

In this unit, we'll explore the Azure technology options that are available to automate and integrate your business processes.

## Common business issues
In business, one way to guarantee high-quality products and service to customers is to design and implement strict business processes. Such processes may involve multiple steps, people, and software packages. Each process may run in a simple line of activities that workers perform one after the other or they may branch or loop. Each process may also run quickly or take days or weeks to complete.

A business frequently runs into issues when it merges with a second business or integrates with a partner organization. How can administrators integrate the separate processes used in the two organizations, which may have been implemented using different software?

Business processes modeled in software are often called workflows. Azure includes four different technologies that you can use to build and implement workflows that integrate multiple systems:

- Logic Apps
- Microsoft Power Automate
- WebJobs
- Azure Functions

These four technologies have some similarities. For example:
- They can all accept inputs. An input is a piece of data or a file that is supplied to the workflow.
- They can all run actions. An action is a simple operation that the workflow runs and may often modify data or cause another action to be performed.
- They can all include conditions. A condition is a test, often run against an input, that may decide which action to run next.
- They can all produce outputs. An output is a piece of data or a file that is created by the workflow.

In addition, workflows created with these technologies can either start based on a schedule or they can be triggered by some external event.

