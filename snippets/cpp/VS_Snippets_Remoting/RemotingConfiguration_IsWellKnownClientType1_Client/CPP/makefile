all: RemotingConfiguration_IsWellKnownClientType1_Shared.dll remotingconfiguration_iswellknownclienttype1_client.exe

RemotingConfiguration_IsWellKnownClientType1_Shared.dll : RemotingConfiguration_IsWellKnownClientType1_Shared.cs
	csc /t:library RemotingConfiguration_IsWellKnownClientType1_Shared.cs

remotingconfiguration_iswellknownclienttype1_client.exe : remotingconfiguration_iswellknownclienttype1_client.cpp RemotingConfiguration_IsWellKnownClientType1_Shared.dll
	cl /clr:pure remotingconfiguration_iswellknownclienttype1_client.cpp



