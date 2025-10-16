<?xml version="1.0" encoding="UTF-8"?>
<!-- Copyright (c) .NET Foundation and contributors. All rights reserved. Licensed under the Microsoft Reciprocal License. See LICENSE.TXT file in the project root for full license information. -->


<Wix xmlns="http://schemas.microsoft.com/wix/2006/wi">
    <Fragment>
        <UI>
            <Dialog Id="CustomInstallDirDlg" Width="370" Height="270" Title="!(loc.InstallDirDlg_Title)">
                <Control Id="Next" Type="PushButton" X="236" Y="243" Width="56" Height="17" Default="yes" Text="!(loc.WixUINext)" />
                <Control Id="Back" Type="PushButton" X="180" Y="243" Width="56" Height="17" Text="!(loc.WixUIBack
# .vscode