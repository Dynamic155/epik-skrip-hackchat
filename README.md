while wait() do
workspace.CommunicationRelays.Transaction.CollectBonus:InvokeServer(tick() - workspace.CommunicationRelays.DataManagement.GetOSTime:InvokeServer())
workspace.CommunicationRelays.Transaction.CollectBonus:InvokeServer(tick(), workspace.CommunicationRelays.DataManagement.GetOSTime:InvokeServer())
end
