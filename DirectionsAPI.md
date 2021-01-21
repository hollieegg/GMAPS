# Google Map Directions API Task 

## URL
https://maps.googleapis.com/maps/api/directions/json?origin=Toronto&destination=Kleinburg&mode=bicycling&key=AIzaSyCdRsZtnAqzKfcQqbm-LgV-yw1vpSa1YNY

## JSON Response
```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpTvG15DL1IkRd8S0KlBVNTI",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJdTK7TQskK4gRZoxrY0pfzHs",
         "types" : [ "political", "sublocality", "sublocality_level_1" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.8385567,
               "lng" : -79.3826048
            },
            "southwest" : {
               "lat" : 43.6510325,
               "lng" : -79.62341619999999
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "40.3 km",
                  "value" : 40261
               },
               "duration" : {
                  "text" : "2 hours 25 mins",
                  "value" : 8718
               },
               "end_address" : "Kleinburg, Vaughan, ON L0J, Canada",
               "end_location" : {
                  "lat" : 43.8385567,
                  "lng" : -79.62341619999999
               },
               "start_address" : "Toronto, ON, Canada",
               "start_location" : {
                  "lat" : 43.6532565,
                  "lng" : -79.38303979999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 154
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 140
                     },
                     "end_location" : {
                        "lat" : 43.6520699,
                        "lng" : -79.38291359999999
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eWalk your bicycle\u003c/div\u003e",
                     "polyline" : {
                        "points" : "{_miG~nocNv@U`@MdA[`@MNEBA@?@A@@@??@@B@B?@Hj@@B"
                     },
                     "start_location" : {
                        "lat" : 43.6532565,
                        "lng" : -79.38303979999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 43.6521297,
                        "lng" : -79.3827601
                     },
                     "html_instructions" : "Sharp \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                     "maneuver" : "turn-sharp-right",
                     "polyline" : {
                        "points" : "mxliGdnocNA?A?AA?AEY"
                     },
                     "start_location" : {
                        "lat" : 43.6520699,
                        "lng" : -79.38291359999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "89 m",
                        "value" : 89
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 43.6528624,
                        "lng" : -79.3831515
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yxliGfmocNIRcA\\cAZ"
                     },
                     "start_location" : {
                        "lat" : 43.6521297,
                        "lng" : -79.3827601
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 327
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 43.6524201,
                        "lng" : -79.3871006
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "k}liGtoocNAHAFCFAHAH?D?j@?p@@d@?nAAL?L@H?JLhAVrBz@|G"
                     },
                     "start_location" : {
                        "lat" : 43.6528624,
                        "lng" : -79.3831515
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 870
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 236
                     },
                     "end_location" : {
                        "lat" : 43.659884,
                        "lng" : -79.390349
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eUniversity Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "szliGjhpcN{@XuAf@{@Va@L_@Lc@NcBj@UFq@TYJe@Na@Na@Lq@T_AZ}@XYJa@LKDc@Na@La@Na@La@L]La@La@Na@Lg@Pi@Pe@PqA`@i@PQFaA\\"
                     },
                     "start_location" : {
                        "lat" : 43.6524201,
                        "lng" : -79.3871006
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "73 m",
                        "value" : 73
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 43.6605155,
                        "lng" : -79.3906021
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQueens Park\u003c/b\u003e",
                     "polyline" : {
                        "points" : "giniGt|pcNyAd@E@IBUD"
                     },
                     "start_location" : {
                        "lat" : 43.659884,
                        "lng" : -79.390349
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 107
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 43.6598335,
                        "lng" : -79.3906016
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eQueens Park\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "gmniGf~pcNCFAFAF@D?F@DBHDJHIFEDCFCd@O|@Y"
                     },
                     "start_location" : {
                        "lat" : 43.6605155,
                        "lng" : -79.3906021
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.1 km",
                        "value" : 4124
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 875
                     },
                     "end_location" : {
                        "lat" : 43.6509771,
                        "lng" : -79.440017
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCollege St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}hniGf~pcNBVJx@DVBXNbAHt@NdAF\\Hl@d@rDVpBZzBVtBHh@D\\Fl@B\\P~APxA@JDXFn@^`DLv@NrABNNvAJv@@H@F?F?F?JAl@?L?H?F@F?FDZFj@Jv@F^D`@BRLdABRTtAPrADd@@JF^VzBHn@NzAXdCBLVvBV~B\\tCBVNfALfAHt@VvBp@rFp@vFp@pFr@zFNpA`@hD@P@J?V?T?HAL?DC\\CZCVEb@Eh@CZCZAJARAJANAHAJANALANANAPAX?L?L?L?FAH?L@L?J?H?J?F@J?L@P@V@Z@@@T@L?BR`BR~AJt@r@rFp@pFr@vFt@xFBX@FHj@L~@Jz@Fh@F^ZjCd@rDBL\\nC@FRxAFf@Fb@@J@F?D?F?D?DAL?HAB?HCNCT?H?HAN@H?J@H@PHj@VzB`@jDLz@Ht@PtAf@dED^NnAF`@P|AFh@Fb@Dh@D`@Hv@@NZjCZhCNjADZ^bD@JBJBLBFBFFLHN"
                     },
                     "start_location" : {
                        "lat" : 43.6598335,
                        "lng" : -79.3906016
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 849
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 168
                     },
                     "end_location" : {
                        "lat" : 43.6583452,
                        "lng" : -79.44273389999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLansdowne Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sqliGbszcN_@Jw@T_AXsA^yBl@m@Pm@Pk@Na@JSFGBE@I@g@Pm@Nu@TQD]Jk@POD_AVoBj@k@N]Je@Ns@Rs@Rq@PWHa@JkA\\IBC@C?A?C@C?A?C@C?EAG?E?KAGA"
                     },
                     "start_location" : {
                        "lat" : 43.6509771,
                        "lng" : -79.440017
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2814
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 672
                     },
                     "end_location" : {
                        "lat" : 43.6511421,
                        "lng" : -79.47625909999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBloor St W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "u_niG`d{cNJr@XzBNhABRBRVlBBZDR@JFb@@J@DD\\VxBDRFh@BRDZL`A^~CD^@JBRLt@T|ABVD\\T`BFf@Fd@J~@Hn@Jz@R~ALlAXtCb@fDTdBV~ABPnAtJVxBLh@R|Aj@pEBLDb@N`ALfAT`BF`@Hp@?JBLHf@Jv@x@bGZ~B\\pCd@pD\\fC^rCVfBFb@F`@x@fGR|AT|APpAPvAF`@LbA^rCHn@Lz@n@tE\\lCT`Bp@zENdA^xC"
                     },
                     "start_location" : {
                        "lat" : 43.6583452,
                        "lng" : -79.44273389999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1674
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 327
                     },
                     "end_location" : {
                        "lat" : 43.6655846,
                        "lng" : -79.4821065
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRunnymede Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "srliGruadN[He@LGBWHKDuH`CgHzBIBsDjAc@L_@LA@eAZk@Pw@Vu@VoA`@cA\\gA\\oA`@yBp@[JaAXcA\\_ATUDaARy@PMDA?I@mBb@OBOFUFYJaDbAsA`@kA^{Ad@_Bf@mA^YH_AX"
                     },
                     "start_location" : {
                        "lat" : 43.6511421,
                        "lng" : -79.47625909999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1339
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 326
                     },
                     "end_location" : {
                        "lat" : 43.665593,
                        "lng" : -79.49874070000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDundas St W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{loiGdzbdNA|BAjDA~C?xA?~@ApC?vA?~AAfA?j@?fAAbB?x@?jA?d@A|AAnAChAAz@A`@AbA@h@?bB?p@?H@f@?~@?|AAlCC`G?fBArB?n@?\\?`@At@@b@@n@@\\?P@PHnADp@@TBR?D"
                     },
                     "start_location" : {
                        "lat" : 43.6655846,
                        "lng" : -79.4821065
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "40 m",
                        "value" : 40
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 43.6657406,
                        "lng" : -79.4991941
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eScarlett Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}loiGbbfdNETCLEPCNCDEL"
                     },
                     "start_location" : {
                        "lat" : 43.665593,
                        "lng" : -79.49874070000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2341
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 503
                     },
                     "end_location" : {
                        "lat" : 43.6844383,
                        "lng" : -79.511702
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eScarlett Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{moiG|dfdN_@BG@M@M@_@FC?g@LYFIDQDMDIBKFSHGDQLSNwCbCuAhAGFaAx@uBdBmCvBw@p@QNeAz@{AlAo@h@i@b@GDKFIDGDIDUJa@NMDoAX[Fy@Xu@XsAd@]NUJ[PCBYRWRGDcA`AEBUVQLOLMFOJMDMDSFMBUBS@I?I?QAOK}@IW?K@QDE@UFUHEBi@Vs@b@k@d@aAt@YP_@b@oAz@MH_@V_@VABWNA@WNkBlAi@^gAv@eAr@QJ}@n@k@`@i@`@i@`@KHe@`@_@\\C@YVaAt@_Ap@YRYDC?WR}@l@YTSNuAbA"
                     },
                     "start_location" : {
                        "lat" : 43.6657406,
                        "lng" : -79.4991941
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1579
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 307
                     },
                     "end_location" : {
                        "lat" : 43.6974092,
                        "lng" : -79.5147849
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wbsiGbshdNEGECCCE?CAE?OBQDMDE@EB[RQLWRSNIFA@EB[LC@_@JG@C@UBI?YBS@IBE@E@KFIDC@EDYROLMHGDQJEBMFIBIDgBf@ODQDc@JG@IBC@IDA@GD]`@EDMJGDQLEB_@RaAf@a@RA@GBEBABCBEFA?S`@C@?@IJKHEBA@YTC@C@YDE?UBI?CAMAAAAAAAACACACACKc@CGOe@AESg@ACM]IOIKIGCAEAQCIAG?S?i@?Q@I@I@?@OD]LIBG@C?G?a@@]@W@K?C?M@MBC?OFSDC@O@KCOEUGOEMAC?m@Ie@?UB]LE?[DG@I@YBw@FOBI@OBWFYJ[Ha@LODkBf@O@KBC?C?EAC?EAE?E?G@EBGB[LE@GBE?I@C?A?a@Cc@C]CE@C@A?A@A@ABCDAB?D?D?B?F"
                     },
                     "start_location" : {
                        "lat" : 43.6844383,
                        "lng" : -79.511702
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 368
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 43.6977355,
                        "lng" : -79.51918909999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ysuiGjfidN@FFXDb@@LBZ?LAR?XAhAAJ?b@?p@?P@fAFbABp@ARAH?HCPE\\?BIj@AHG\\ADGVGTABIVELEPSh@"
                     },
                     "start_location" : {
                        "lat" : 43.6974092,
                        "lng" : -79.5147849
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 896
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 174
                     },
                     "end_location" : {
                        "lat" : 43.702601,
                        "lng" : -79.52713969999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "{uuiG|ajdNILKNMNKNIHW^OPMRGHIH]ZKLKJCBCBGHCFGJ?BCDEHGJEFC@EDGBOBK?K?I?A?S@OBE?KBOBC@M@CAA?CAAACEE?E?C@QJUPOLUPUVILKPADABEJAJCNAHAXALC\\CPALE\\EZCRGXIT?LCJEXYdAENOh@Qj@IZWz@M`@_@nAYdA{@vC[`ACHM^EJUb@S\\U^"
                     },
                     "start_location" : {
                        "lat" : 43.6977355,
                        "lng" : -79.51918909999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 123
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 88
                     },
                     "end_location" : {
                        "lat" : 43.703516,
                        "lng" : -79.5263537
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eWeston Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "gtviGrskdNO@GAGAIIEEQQIECACAEGCGCECCCCCACAECCAACCCCGAAAACEGEKICCAAOW"
                     },
                     "start_location" : {
                        "lat" : 43.702601,
                        "lng" : -79.52713969999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 906
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 241
                     },
                     "end_location" : {
                        "lat" : 43.7089185,
                        "lng" : -79.5341045
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWeston Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_zviGtnkdNi@nAaBnDCH_AtBwBxE_@z@]x@e@lACHQd@]`AWt@CLELERGTGZEXA@E^Ib@C^GVCJCHGNCHGLEFEFIHGFIHWPi@Vq@XUDYJOFKDWFaBt@_@PSHQHMFi@R"
                     },
                     "start_location" : {
                        "lat" : 43.703516,
                        "lng" : -79.5263537
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 242
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 87
                     },
                     "end_location" : {
                        "lat" : 43.7092424,
                        "lng" : -79.5366188
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFairglen Crescent\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w{wiGb_mdNF\\R~ABPZjC@LAHALAHMZSh@g@pACFEFABA@C@C?A@A?C?CAC?CACA"
                     },
                     "start_location" : {
                        "lat" : 43.7089185,
                        "lng" : -79.5341045
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 469
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 43.7118231,
                        "lng" : -79.539028
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w}wiGznmdNEJAD?F?D?BBH@HHPFJDHHPDHJPBH@H?B?D?JAHAFAJEPSp@KTINILe@\\EDWREBYR[R_@NEBa@RI@M@WGSKC?WUCA[KEA[KIAOCAAC?C?C?A?A?A?A@A?C@EDWRC@[VWPABCB"
                     },
                     "start_location" : {
                        "lat" : 43.7092424,
                        "lng" : -79.5366188
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 3967
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 705
                     },
                     "end_location" : {
                        "lat" : 43.7341188,
                        "lng" : -79.55146139999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{mxiG|}mdNECEACCCAA??AAAAA?A?AAAG[?AAA?AAACCAAAAAACACAQA_@EgAK{AOSGMGIEIEA?CACAC?A?ICC?CAC?A?C?A?A?A?C?E?A@C?A@MFIDWNA@A@MJGDCBABABA@ADA@?@AD?BAD?F?FA@?@?DABABABCDEHCBABAB?@ABA@ER?@CJAB?@A@KNC@CFA@?@?@?DBP?B?@@B?@?@?@?@AB?@ANG\\G^EX?D?@?@?D?B?B?H@D?B?B?@?@ABAFCDABCDCBCDABCBA@CBEDEDEDGBCBIFEBA@A@ABA@ABCHYj@Wj@Q\\IRQ^OVEFCDEBEDEDKHEDSJOJIDEDC@CDEBGFCDCDMTGHCDCDCHEJGNSf@CFGPAFCDGZAFAD?@CDADADCDABCBCDQPSTIJONIHKJA?IHKJEDGBKDG@IBUHG@E@C?E@OAQCC?EAEAECWOECKGCACAMGCAKCC?C?C@A?A?A?A?CAA??AA?AAAACA?AAACGCGAGOa@CKCGCICCAAACAACAKGECICQICACAA?E?E?E?K@I@A?I@K?E?K?MDEBIDA?A@CBEDCBMNA@C@A@A?A?I@GCQEA?EAA?E?C?CAC?CAAACASKGEOMIICCCCEGEECIEKAG?I?C?CAC?AAAGGEEEEGG]WCCCAECOEEAGCKAUEKCA?CAAACAAACECCEGGIAAAAAAAAECGECAAAKEOEKGA?CCCCCCAAKQYe@EIACACCCCGGSUg@GSAAACAAAAACCACAA?C?CAA?C?[BE?C?E?E?C?C?EAE?ICCAC?ICCAAAEAEECECEGIAC?AAC?AAA?KAIAOAY?Q?ECi@AC?CAE?A?AAC?AAAAACAMEe@SCAAAAAAAAA?AAA?AAC?AAC?AAC?ACQCIACCGAECEAAAAACECECECCAECE?OEg@KKAMCIAYCCAA?A?CAAAAACAACCAACGIACAAACEECCCCCCCCAAEAA?C?SCA?QCGAC?CAICCACACACACCCAAAACCCGIEGEECEACCEEGCEAEEICEACCECECCw@aAYW[YUU]WCAE?_@EC?YAC?C?E@C?A@A?A@CBCBEDEHCDCFCFABGHGFCBEDA?A@A@A?G@E?G?GAE?IAEAGAKEEAEAOAA?C?C@C?GDSJC@OPA@A@C@A@C?E?C?CAA?AAUWCACCCAECGCGCGAC?CAC?CAA?C?C?G@G?E@E?i@H{@JYBg@H]Fc@F?@M@QDGBG?C@SBO@O@O@U?Q?O?AAM?I?GAQAQCMAC?E?C?C@E@CBCBCDEHENGROb@ENAJ?BAJALAN?D?J@X@T@LD\\F\\BJ?DBHBX@J?F@L?JAJ?HCHAFCFEHELADAD?H?D?B@D@B@B@BBDHJHLBF@F@D@FFp@B\\BP@P@X@Z@V?^?P?@APC^Eb@UhBA@CNCJAHCDCDCBADGFIFIFKFMHIFCDEFCDADIPGPCHCHELCFADCDCDEFONEBABCFQx@WdAA?Kd@K`@GZGXCNCNAFCFAFEHIPELEFCHAH?DAF@J?FBT@J@D?D?HCRC\\Iz@I~@It@ANCNANERM|@Kn@ABSlAETCN?J?F?@?D@F@HBRDt@Dd@?HB`@@D@\\?Z?RALAHGV"
                     },
                     "start_location" : {
                        "lat" : 43.7118231,
                        "lng" : -79.539028
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 943
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 167
                     },
                     "end_location" : {
                        "lat" : 43.7420754,
                        "lng" : -79.54817330000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gy|iGrkpdNOGg@UIEGCMGKEICEAC?Q?O?e@DO@U@S@I?I?MA_@Ce@CIAEAIAKCQEiAYOEIAQ?C?S?M?O?QAUCKCKCSGSIOESIQIOIw@_@e@WUMg@[{@i@qD}Bo@]]Qq@]w@i@UQEEi@_@WUGEGCCCCACAC?GAE@W@W@W@E@G?C?[G"
                     },
                     "start_location" : {
                        "lat" : 43.7341188,
                        "lng" : -79.55146139999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 147
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 43.7431288,
                        "lng" : -79.5484101
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_k~iG`wodN?BABCJABCFAFCHCFELCDCBA@C@C@A?M@]Dm@LC?E?C?C?C?CACACACCACMQGKIQ"
                     },
                     "start_location" : {
                        "lat" : 43.7420754,
                        "lng" : -79.54817330000002
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1276
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 212
                     },
                     "end_location" : {
                        "lat" : 43.7434989,
                        "lng" : -79.5629654
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qq~iGpxodNKL[h@OXOZc@v@INe@x@EFCHCDCFEPAHGNCLELEVGXEZGVCT?@CTI|@?JAH?H?J?V@V@P@FBVFp@J`ABNHb@BNJb@Rr@BHBLBLDRFf@BRF\\Hr@N~@BLBN@R@P?PARANCNCPI\\EPAHCR?RAR?F?FHfAFd@DV@D@DBDBFDD@D@BFLDLBLDLDNBJBH@FFLDRBJ@H@H@V@R@XBr@@b@@Z?PAb@Ez@Cb@?R@HDN?BDJBLBD@B@B@BFL@B@D@D?B?J@P?DAV?\\AN?FAHAHCHAFW`ACJENEJEFMPGJEHEHELCHGXCF?FEt@Ef@?H?D@NFPHZDJ?D@H"
                     },
                     "start_location" : {
                        "lat" : 43.7431288,
                        "lng" : -79.5484101
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1761
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 319
                     },
                     "end_location" : {
                        "lat" : 43.7500134,
                        "lng" : -79.5775506
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{s~iGpsrdNCHUb@iArBcAbCcAlBq@rAKRUr@GVCNCNE^EDEDGFIFYPQJKDE@C?E?EAUKEA[OKEc@QA?A?C?A@CBCBEHI`@DZ@HFTBFBFDF?DBJ@H@HB^?FB`@?J?JANCVG`@Gn@CPG`@ALANG^CVIX?BGPEJCFEFIHGFEBGBIDGBEBIBABABADAFGf@CLCFEFIJQTGHELCLCNCPEj@Gd@ADADEPGLC@CBA?EBG@CAGAYIGAA?A@A@ER?DABABC@C@A@I@U@C?I?GAQAA?G@IBGDEDIJEJGHABKLKLKJCBMHMFMFi@P]Jg@Li@NUHMFQJCBC@OPMLMRGLM\\KTERCHAJG`@?@AJ?F?F?F@L@D@N?Z?D@r@@\\@hBAP?DAHCLEJEHGLGHCDEBE@GBUJMJEFCFAD?@?DAH@F?DFr@@F@FFNP\\Vj@LXHVDLBLDRFNDHBFBBBBLD@?JDTFLDF@H@B@LH"
                     },
                     "start_location" : {
                        "lat" : 43.7434989,
                        "lng" : -79.5629654
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 366
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 72
                     },
                     "end_location" : {
                        "lat" : 43.7514304,
                        "lng" : -79.5813924
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "q|_jGtnudNBVNxA?N?T?DADAFENCJEHCBSTMLS\\CFYt@IVIXIXER?@CLI^Kf@Wj@MTe@~@KVGNCBIRITMX"
                     },
                     "start_location" : {
                        "lat" : 43.7500134,
                        "lng" : -79.5775506
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 152
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 43.7518117,
                        "lng" : -79.58308269999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "me`jGtfvdN@T@H?P?VAV?@?@ADEJKXKTKVMXKRM`@AFAD?F?D@D@F@HBL"
                     },
                     "start_location" : {
                        "lat" : 43.7514304,
                        "lng" : -79.5813924
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1293
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 267
                     },
                     "end_location" : {
                        "lat" : 43.7602601,
                        "lng" : -79.5835043
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eHumber River Recreational Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yg`jGfqvdNOHGDC@A?I?O@K@O@E@A?A@A?EBA?A@CBKJGHORu@`AEDCDCBEBWPi@b@EBc@\\OLUREDQJKDWJULIFOHA@QJe@^EDEDSPIHKHGFGBKBGBM@S@I?C?A?YAUCI?G?E?G?G@K@WDc@Fk@JWBK@I?K?IAI?UGQCUGMEQEMGMEUEa@OMICAOMSOQSGICCACCAAACCC?_@OMEIGKEIIKKKG]YSQMIIGOKEEEIGGACAECEAAAEACAGCKAMG_@Em@Gu@CSEUGYSeAIe@GSGOEIAAGIKI[WICIEK?I@C@E@GFCDELGRGRADCPAh@D~@BT?H@THz@@N@D?B?B?BAB?@ABA@GF"
                     },
                     "start_location" : {
                        "lat" : 43.7518117,
                        "lng" : -79.58308269999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 832
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 219
                     },
                     "end_location" : {
                        "lat" : 43.764165,
                        "lng" : -79.5749086
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "s|ajGzsvdNQ_AIc@Ke@CII]ACMi@K]GQKYGSISO_@O]MYEGO_@KOIOIQOUEGGI[]Yc@c@m@GKm@_AEEs@eAQWMSMUQ[Yi@_@m@?A[o@IUOa@EMK_@EO?CGUMi@Iq@G_@Km@M_ACUG]Iq@M}@AKGe@EQCMAMAKAM?A"
                     },
                     "start_location" : {
                        "lat" : 43.7602601,
                        "lng" : -79.5835043
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "10 m",
                        "value" : 10
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 43.7642423,
                        "lng" : -79.5749603
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eSteeles Ave W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_ubjGd~tdNOH"
                     },
                     "start_location" : {
                        "lat" : 43.764165,
                        "lng" : -79.5749086
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "24 m",
                        "value" : 24
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 43.764303,
                        "lng" : -79.5746741
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSteeles Ave W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oubjGn~tdNCYG_@"
                     },
                     "start_location" : {
                        "lat" : 43.7642423,
                        "lng" : -79.5749603
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.8 km",
                        "value" : 8837
                     },
                     "duration" : {
                        "text" : "31 mins",
                        "value" : 1852
                     },
                     "end_location" : {
                        "lat" : 43.8303065,
                        "lng" : -79.614003
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eIslington Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 17\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{ubjGt|tdNURoAv@]TA@ABMT_@X_@PwA|@?@qBnAe@X}A~@MHQJe@\\ID_Al@QLQJa@V{@l@s@b@a@VmAv@aAj@]Tk@`@ULUJYJe@Pc@NaARQDO@WBA@S@G@I?G@Y@{@@M?]?[@[@O@QBI@OBYFYHSFWJ[LSJcBx@GBYNIDg@TIDc@R[RKFk@^e@^C@[Xi@b@e@`@IHONMJON[^a@d@EF[^CB[`@SZ[f@c@n@KPKPOVg@|@q@vAm@rAIPc@`Aa@dAyCjG_@lAUt@Qd@GPSl@Sr@KXCHO`@O`@CJEHUb@?@ILCFGHGHEHIHEDCDWVOT_@VIFQHCBGBID_@N}@XoAf@E@YJC@WFUFYBY@QBY?A?]AC?SA[EYG[ICAWK[MMIIEWOSQQOm@m@AAIIMQMMa@[mAs@u@Qk@Ic@@U@W?iALSBOBs@DO@C?ODOBQ?E?I?QCKAc@EM?[?UKSMYSYYSUOSMQKUKQISa@iAIWISYq@GQSe@Wk@Se@Ya@SYSY[_@[[a@_@MKe@YCA]QSKSKSIICOGUESCe@MmBa@mBSYEC?[?K?Y?U?Q@W?o@@}ADs@@S?U@aA@{@Ba@?W@c@?s@@G?K@G?U?e@@{@@cBBsDHA?qEJaFJW?qAByBDiBBWCWAaAAs@?Y?YBS@Q@A?QBc@Jy@Pu@RYLWJ[Pu@`@}@l@gC|A}BlAa@RSJc@XcAn@YN]PsDpBm@^iBjAo@^SPGVEDs@x@KLEFY\\[^[d@gCbEKTmAvBUN{DbHu@vAsAbC_AfBg@bAy@pAsAzBoAbCGRIViBlDeApBaAfBa@p@e@t@{@xAo@hAORu@rAqA~Bq@nASLs@tA]n@g@|@}ApCQ\\}@bBiAtBwAxB}@hASTeB|AsAdAIHOJg@^}Az@oB~@EDMR_Bp@_Bv@MHqAl@a@PUJs@\\oAl@wAn@y@`@YLSJ{@d@]@GBqBvAi@`@y@r@UTKJg@f@Y\\Y^uAjBEZINk@bAWd@y@hBeAlCMV"
                     },
                     "start_location" : {
                        "lat" : 43.764303,
                        "lng" : -79.5746741
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "18 m",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 43.8301697,
                        "lng" : -79.614131
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSunset Ridge\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mrojGnr|dNZX"
                     },
                     "start_location" : {
                        "lat" : 43.8303065,
                        "lng" : -79.614003
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 358
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 43.8319778,
                        "lng" : -79.6176265
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qqojGhs|dNMh@AHAF?H@Z@LIXAHEPMNQTMZK^Kd@O`@CFSVe@b@URUX[n@[x@[h@a@n@CBCDEJAFADAP"
                     },
                     "start_location" : {
                        "lat" : 43.8301697,
                        "lng" : -79.614131
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "48 m",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 43.8324015,
                        "lng" : -79.61759579999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eIslington Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{|ojGdi}dNKBC@C?E?E?GAk@I"
                     },
                     "start_location" : {
                        "lat" : 43.8319778,
                        "lng" : -79.6176265
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 830
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 177
                     },
                     "end_location" : {
                        "lat" : 43.8385567,
                        "lng" : -79.62341619999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eIslington Ave\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o_pjG~h}dNQRiA|AYZcApAe@j@g@h@q@v@GF_@`@q@p@_@\\SP_@\\SPq@h@qAdAeBtAoCvB_At@yGlF"
                     },
                     "start_location" : {
                        "lat" : 43.8324015,
                        "lng" : -79.61759579999999
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "{_miG~nocNxEwAR|@K]sCvAIb@@~F`BfNoFfBqIrC}HhCsQbGeCnAJb@^WbBi@NpAb@jD|CrUfDxYj@nIjFvc@hGvg@r@~Io@lIExErGfj@bEx[K~C~Edb@~BjSLl@JTUZeI|BiD~@iElAgTfG]@a@Cx@lGr@rFbBfNtCdUpJju@dJfr@lCnSpB`O`A`H^xC[Hm@Pc@N{WlIuJ|CaZdI}PnFgBh@_AXA|BCjI?xCCpKAvEK`OGdf@XlHYrBiDf@mBz@s\\jX}FhBoGxCgDrC{B\\wBWy@PaHzE{StN{GlFqGdEaAGsBpAmEfAeBjAuEtAaGrDsBrBuA@i@cBgAuBcCC}Eh@yBE{DJyKxBuBZqBEIf@\\fPkA~GsEhGk@dAcANyBFyBtBUbBaCvLiEvNeAlBi@Ks@q@]We@i@EEOWi@nAeBxDwDnIgBlEkAjDs@rDm@|BkDlBuF|Bw@ZZ|B^tDyAbEYBKh@x@hBInAs@dBiAz@uCrAiCeAwAVmAd@Og@_GaAqA]cB~@Q`Au@tCYtC_@dA_CrDuCdDkBxDkB~CeAr@yALsBs@a@e@e@kA{@_@wBZa@^u@IiB}A}AeB_E_CcBeDcBEu@_AWsCgA{@kAsAcFcBiA{@kEcFuAG]ZmAx@eAQ}@f@gA_@sDJcHv@gCDm@|BFjCTfBOrAEv@b@|@XhEc@tFeB`CcBfEqBvH_@fIcAvIVzEKbAiAg@uBMaDCwG{@cSqKiDeCaB@u@P]z@kCJk@a@_BvCiAdCaA`IhBzLp@hF]pCPpE\\v@~@rGErFX~@@xDiAxCg@hDZhB_InPs@rBcBV{Ag@Wr@RbAT|AUdEi@fDy@z@_B`Dc@~Ck@Tm@Pm@PcAFcArAgExAiBvAu@nCBbBApFs@|@q@~@~@jDx@bCnAb@^d@NdCy@zAoE|La@pCm@tBi@pBGh@WF}@LaBpBaGfEsB~A{A`@_G\\}Ba@iCmAqDiCcBwB}@{GqAaC_AHWz@BpCN|BEJo@aCeAsDcBsDqH_LaCoFgAsGw@uFEi@SO]KqBrAeD~BeIdFeJ`G{GjDuJp@gD|@yFnCaK`JkC|DaKfTqEnMgD`D_GpBwCDaDcAsCkCqEkB{CP}CXqCWqC_DmC_H}DcF}C{AeJsAiOT}c@v@wI@kFpA{^hTeDpEwF`JeKfRgM`VmKzQmJtPsFnIsExDwMhHyLvFuBv@kFbEyFlIeDtHLbACPElAg@`Au@bCsAvAyCrFe@d@s@K{ApBkDbEsFrFsU`R"
         },
         "summary" : "Humber River Recreational Trail",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
