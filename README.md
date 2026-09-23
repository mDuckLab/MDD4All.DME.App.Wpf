# MDD4All.DME.App.Wpf

The desktop host of MDD4All.DME, the object graph editor application.

A WPF window with a BlazorWebView in it: the window owns the title, the culture and the question asked before it closes, everything inside it is drawn by the editor's Blazor components. This repository holds the host and the wiring - which implementation answers which contract - and nothing else. The editor itself lives in MDD4All.DME.Views and MDD4All.DME.ViewModels.
