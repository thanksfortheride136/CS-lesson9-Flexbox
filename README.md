# CS-lesson9-Flexbox

warm-up B64: PCFET0NUWVBFIGh0bWw+CjxodG1sPgo8aGVhZD4KICAgIDx0aXRsZT5GbGV4Ym94IFdhcm0tdXA8L3RpdGxlPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJ3YXJtLXVwLmNzcyI+CjwvaGVhZD4KPGJvZHk+Cgo8IS0tIFdhcm0tdXAgRXhlcmNpc2U6IENyZWF0ZSBhIEZsZXggQ29udGFpbmVyIC0tPgoKPCEtLSAxLiBDcmVhdGUgYSBkaXYgd2l0aCB0aGUgY2xhc3MgImZsZXgtY29udGFpbmVyIiAtLT4KPCEtLSBZb3VyIGNvZGUgc3RhcnRzIGhlcmUgLS0+CjxkaXYgY2xhc3M9ImZsZXgtY29udGFpbmVyIj4KICAgIDwhLS0gMi4gSW5zaWRlIHRoZSBjb250YWluZXIsIGNyZWF0ZSB0aHJlZSBkaXZzIHdpdGggY2xhc3NlcyAiYm94MSIsICJib3gyIiwgImJveDMiIC0tPgogICAgPCEtLSBFYWNoIGJveCBzaG91bGQgY29udGFpbiBzb21lIHRleHQsIGUuZy4sICJCb3ggMSIgLS0+CiAgICA8IS0tIFlvdXIgY29kZSBzdGFydHMgaGVyZSAtLT4KICAgIDxkaXYgY2xhc3M9ImJveDEiPkJveCAxPC9kaXY+CiAgICA8ZGl2IGNsYXNzPSJib3gyIj5Cb3ggMjwvZGl2PgogICAgPGRpdiBjbGFzcz0iYm94MyI+Qm94IDM8L2Rpdj4KICAgIDwhLS0gWW91ciBjb2RlIGVuZHMgaGVyZSAtLT4KPC9kaXY+CjwhLS0gWW91ciBjb2RlIGVuZHMgaGVyZSAtLT4KCjwvYm9keT4KPC9odG1sPgoKLyogV2FybS11cCBDU1MgZm9yIEZsZXhib3ggKi8KCi8qIDEuIFNlbGVjdCB0aGUgImZsZXgtY29udGFpbmVyIiBjbGFzcyBhbmQgYXBwbHkgRmxleGJveCAqLwouZmxleC1jb250YWluZXIgewogICAgLyogQXBwbHkgZGlzcGxheSBwcm9wZXJ0eSB3aXRoIHZhbHVlIGZsZXggKi8KICAgIGRpc3BsYXk6IGZsZXg7IC8qIFlvdXIgY29kZSBoZXJlICovCgogICAgLyogU2V0IGEgYmFja2dyb3VuZCBjb2xvciAqLwogICAgYmFja2dyb3VuZC1jb2xvcjogbGlnaHRncmF5OwoKICAgIC8qIFNldCBhIGhlaWdodCBmb3IgdGhlIGNvbnRhaW5lciAqLwogICAgaGVpZ2h0OiAyMDBweDsKCiAgICAvKiBBZGQgc29tZSBwYWRkaW5nICovCiAgICBwYWRkaW5nOiAxMHB4Owp9CgovKiAyLiBTdHlsZSB0aGUgYm94ZXMgKi8KLmJveDEsIC5ib3gyLCAuYm94MyB7CiAgICAvKiBTZXQgYSBiYWNrZ3JvdW5kIGNvbG9yICovCiAgICBiYWNrZ3JvdW5kLWNvbG9yOiBza3libHVlOyAvKiBZb3UgY2FuIGNoYW5nZSB0aGUgY29sb3IgKi8KCiAgICAvKiBTZXQgd2lkdGggYW5kIGhlaWdodCAqLwogICAgd2lkdGg6IDEwMHB4OwogICAgaGVpZ2h0OiAxMDBweDsKCiAgICAvKiBDZW50ZXIgdGV4dCBpbnNpZGUgdGhlIGJveGVzICovCiAgICBkaXNwbGF5OiBmbGV4OwogICAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7CiAgICBhbGlnbi1pdGVtczogY2VudGVyOwoKICAgIC8qIEFkZCBtYXJnaW4gKi8KICAgIG1hcmdpbjogMTBweDsKfQo=

Warm up Improved Good Looking B64: PCFET0NUWVBFIGh0bWw+CjxodG1sPgo8aGVhZD4KICAgIDx0aXRsZT5GbGV4Ym94IFdhcm0tdXA8L3RpdGxlPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJ3YXJtLXVwLmNzcyI+CiAgPGxpbmsgaHJlZj0iaHR0cHM6Ly9mb250cy5nb29nbGVhcGlzLmNvbS9jc3MyP2ZhbWlseT1Tb2ZhZGkrT25lJmRpc3BsYXk9c3dhcCIgcmVsPSJzdHlsZXNoZWV0Ij4KPC9oZWFkPgo8Ym9keT4KCjwhLS0gV2FybS11cCBFeGVyY2lzZTogQ3JlYXRlIGEgRmxleCBDb250YWluZXIgLS0+Cgo8IS0tIDEuIENyZWF0ZSBhIGRpdiB3aXRoIHRoZSBjbGFzcyAiZmxleC1jb250YWluZXIiIC0tPgo8IS0tIFlvdXIgY29kZSBzdGFydHMgaGVyZSAtLT4KPGRpdiBjbGFzcz0iZmxleC1jb250YWluZXIiPgogICAgPCEtLSAyLiBJbnNpZGUgdGhlIGNvbnRhaW5lciwgY3JlYXRlIHRocmVlIGRpdnMgd2l0aCBjbGFzc2VzICJib3gxIiwgImJveDIiLCAiYm94MyIgLS0+CiAgICA8IS0tIEVhY2ggYm94IHNob3VsZCBjb250YWluIHNvbWUgdGV4dCwgZS5nLiwgIkJveCAxIiAtLT4KICAgIDwhLS0gWW91ciBjb2RlIHN0YXJ0cyBoZXJlIC0tPgogICAgPGRpdiBjbGFzcz0iYm94IiBpZD0iYm94LW9uZSI+PGEgaHJlZj0iaHR0cHM6Ly93d3cuaW1kYi5jb20vdGl0bGUvdHQxMzkyMTkwLyI+TW92aWVzPC9hPjwvZGl2PgogICAgPGRpdiBjbGFzcz0iYm94IiBpZD0iYm94LXR3byI+PGEgaHJlZj0iaHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvU3VmamFuX1N0ZXZlbnMiPk11c2ljPC9hPjwvZGl2PgogICAgPGRpdiBjbGFzcz0iYm94IiBpZD0iYm94LXRocmVlIj48YSBocmVmPSJodHRwczovL3d3dy5pZ24uY29tL2FydGljbGVzL2VsZGVuLXJpbmctcmV2aWV3Ij5HYW1lczwvYT48L2Rpdj4KICAgIDwhLS0gWW91ciBjb2RlIGVuZHMgaGVyZSAtLT4KPC9kaXY+CjwhLS0gWW91ciBjb2RlIGVuZHMgaGVyZSAtLT4KCjwvYm9keT4KPC9odG1sPgoKLyogV2FybS11cCBDU1MgZm9yIEZsZXhib3ggKi8KCkBpbXBvcnQgdXJsKCdodHRwczovL2ZvbnRzLmdvb2dsZWFwaXMuY29tL2NzczI/ZmFtaWx5PVNvZmFkaStPbmUmZGlzcGxheT1zd2FwJyk7CgovKiAxLiBTZWxlY3QgdGhlICJmbGV4LWNvbnRhaW5lciIgY2xhc3MgYW5kIGFwcGx5IEZsZXhib3ggKi8KLmZsZXgtY29udGFpbmVyIHsKICAgIC8qIEFwcGx5IGRpc3BsYXkgcHJvcGVydHkgd2l0aCB2YWx1ZSBmbGV4ICovCiAgICBkaXNwbGF5OiBmbGV4OyAvKiBZb3VyIGNvZGUgaGVyZSAqLwoKICAgIC8qIFNldCBhIGJhY2tncm91bmQgY29sb3IgKi8KICAgIGJhY2tncm91bmQtY29sb3I6ICNGMEYwRjA7CgogICAgLyogU2V0IGEgaGVpZ2h0IGZvciB0aGUgY29udGFpbmVyICovCiAgICBoZWlnaHQ6IDUwMHB4OwoKICAgIC8qIEFkZCBzb21lIHBhZGRpbmcgKi8KICAgIHBhZGRpbmc6IDEwcHg7CiAgCiAgLyogQ2VudGVyIHRoZSBib3hlcyovCiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjsKICBhbGlnbi1pdGVtczpDZW50ZXI7Cn0KCi8qIDIuIFN0eWxlIHRoZSBib3hlcyAqLwouYm94IHsKICAgIC8qIFNldCBhIGJhY2tncm91bmQgY29sb3IgKi8KICAgIGJhY2tncm91bmQtY29sb3I6ICM0RDlERTA7IC8qIFlvdSBjYW4gY2hhbmdlIHRoZSBjb2xvciAqLwoKICAgIC8qIFNldCB3aWR0aCBhbmQgaGVpZ2h0ICovCiAgICB3aWR0aDogMjAwcHg7CiAgICBoZWlnaHQ6IDIwMHB4OwoKICAgIC8qIENlbnRlciB0ZXh0IGluc2lkZSB0aGUgYm94ZXMgKi8KICAgIGRpc3BsYXk6IGZsZXg7CiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjsKICAgIGFsaWduLWl0ZW1zOiBjZW50ZXI7CiAgICBib3JkZXI6IDVweCBzb2xpZCAjMjc0MTU2OwoKICAgIC8qIEFkZCBtYXJnaW4gKi8KICAgIG1hcmdpbjogMTBweDsKfQoKYSB7CiAgdGV4dC1kZWNvcmF0aW9uOiBub25lOwogIGNvbG9yOiB3aGl0ZTsKICBmb250LXNpemU6IDUwcHg7CiAgZm9udC1mYW1pbHk6ICdTb2ZhZGkgb25lJzsKfQo=
