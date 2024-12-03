# Flash_ADC
## Hello!
	This design i made by myself with a lot of inside stolen contents :> hahaha
## Ref
	[1] An Efficient Design of 3bit and 4bit Flash ADC, Volume 61– No.11, January 2013, International Journal of Computer Applications (0975 – 8887) by Arunkumar P Chavan, Rekha G and  P Narashimaraja.
	[2] THIẾT KẾ VÀ ĐÁNH GIÁ HỆ THỐNG SAR ADC 10 BIT THỰC HIỆN TRÊN PHẦN MỀM CADENCE, ĐỒ ÁN TỐT NGHIỆP NGÀNH CÔNG NGHỆ KỸ THUẬT MÁY TÍNH, by Nguyen Ngoc Hung, Nguyen Tai Nhan and suppervisor Truong Quang Phuc.
	[3] Two Stage MOS Amplifier - Explained, link: https://youtu.be/ahbx6ItwLdo?si=kmFqx0euDAVH3u0s, by Walid Issa Plus.
## NOTE:
	Instead of GND in 2-stage-op-amp, i have used VSS (-1.2V). Since from later simulation of the Schematic in Ref [1] [2], when i assign V- = 0V (or a number that less than 500mV), the op-amp didn't  work correct :<. 
