<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.1021.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FFeesexe%2F32410210-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FFeesexe%2F32410210-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FFeesexe%2F32410210-NasDHSolutions.json)
- ✨: **💼**: **_Yêu cầu - Bổ sung ghi chú cho mã QR_**
- ✨: Bổ sung tùy chọn thể hiện thêm thông tin khách hàng trên thanh toán QRs ![](https://i.imgur.com/Wj6ke6f.png) ![](https://i.imgur.com/PdmSavK.jpeg)
- ✨: QRData: `00020101021226240006970489011018002726855205140985303704540105802VN5912BVDKTPCANTHO6005HANOI62870112CTXWSQFFGFTA0312BVDKTPCANTHO05120124102115290712BVDKTPCANTHO0819029280 - Tran Van T6304D19C`
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/363
## [v.3.24.1017.0]()
- ✨: **💼**: **_Yêu cầu - Tích hơp Hóa đơn điện tử của VNPT loại MTT(Máy tính tiền) cho Phòng Khám Thiên Ân_**
- ✨: Xử trí riêng đối với VNPT.MTT không sử dụng CDData trên tất cả trường, mà xử lý thay đổi ký tự đặc biệt, tuân thủ qui tắc XML.
- ✨: Xử trí cách lấy Số hóa đơn theo mô tả: "OK:" + pattern + ";" + serial + "-" + fkey + "_" + invNumber + "_" + MCCQT cụ thể trường hợp a đưa : OK:1/002;C24MTT-39Q863DDGW3_25_M1-24-46968-00100000025 thì số hóa đơn sẽ là số 25
- ![](https://i.imgur.com/LgjuExo.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/625
## [v.3.24.1016.2]()
- 🐛: **💼**: **_Yêu cầu - Tích hơp Hóa đơn điện tử của VNPT loại MTT(Máy tính tiền) cho Phòng Khám Thiên Ân_**
- 🐛: Xử lý MMT (VNPT) ![](https://i.imgur.com/Bi8SeAo.png) `<Invoices>  <Inv>    <key>OSDHSLURJW</key>    <Invoice>      <CusCode>2020001989</CusCode>      <CusName><![CDATA[]]></CusName>      <CusAddress><![CDATA[Ấp Bắc 2, Xã Hòa Long, Thành phố Bà Rịa, Tỉnh Bà Rịa - Vũng Tàu]]></CusAddress>      <Buyer>Phạm Thị Lợi</Buyer>      <CusPhone />      <CusTaxCode />      <PaymentMethod>TM</PaymentMethod>      <KindOfService />      <Products>        <Product>          <ProdName>20,00%BHYT (Thuốc&amp;VTYT:197,722; Xét nghiệm:145,200; Công khám:30,100)</ProdName>          <ProdUnit>Lần</ProdUnit>          <ProdQuantity>1.0</ProdQuantity>          <ProdPrice>74603.0</ProdPrice>          <Amount>74603.0</Amount>          <Total>74603.0</Total>        </Product>      </Products>      <Total>74603.0</Total>      <DiscountAmount>0.0</DiscountAmount>      <VATRate>-1</VATRate>      <VATAmount>0.0</VATAmount>      <Amount>74603.0</Amount>      <AmountInWords>Bảy mươi bốn ngàn sáu trăm lẻ ba đồng chẵn</AmountInWords>      <Extra>OSDHSLURJW</Extra>      <ArisingDate>16/10/2024</ArisingDate>      <PaymentStatus>1</PaymentStatus>      <ResourceCode />      <GrossValue>74603</GrossValue>      <GrossValue0>0</GrossValue0>      <VatAmount0>0</VatAmount0>      <GrossValue5>0</GrossValue5>      <VatAmount5>0</VatAmount5>      <GrossValue8>0</GrossValue8>      <VatAmount8>0</VatAmount8>      <GrossValue10>0</GrossValue10>      <VatAmount10>0</VatAmount10>      <ComBankNo />      <CusBankNo />      <ComName>COMNAM</ComName>      <ComAddress>COMADDRESS</ComAddress>      <ComTaxCode>3502208409-001</ComTaxCode>    </Invoice>  </Inv></Invoices>`
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/625
## [v.3.24.1016.1]()
- ✨: **💼**: **_Yêu cầu - Hỗ trợ kiểm tra genQR có thời hạn_**
- ✨: Hỗ trợ thêm expDate khi genQR, truyền lại yyMMddHHmm ![](https://i.imgur.com/13rSPuw.png) ![](https://i.imgur.com/LibahNY.jpeg) 
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/359
## [v.3.24.1016.0]()
- ✨: **💼**: **_Yêu cầu - Hỗ trợ kiểm tra genQR có thời hạn_**
- ✨: Hỗ trợ thêm expDate khi genQR ![](https://i.imgur.com/LibahNY.jpeg)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/359
## [v.3.24.1014.0]()
- ✨: **💼**: **_Yêu cầu - Tích hơp Hóa đơn điện tử của VNPT loại MTT(Máy tính tiền) cho Phòng Khám Thiên Ân_**
- ✨: ***Bổ sung chức cấu hình sử dụng MTT*** ![](https://i.imgur.com/F1aKxt2.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/625
## [v.3.24.1009.0]()
- ✨: Bổ sung thời gian hết hạn của mã QR đối với Vietin, BIDV tùy theo cấu hình
## [v.3.24.1005.1]()
- ✨: **💼**: **_Dự án - Thanh toán QR - HD Bank_**
- ✨: Thay đổi cách thức truyền ***số tiền*** ***{{amount}}***, ***pay_id***: ***{{billNumber}}***
- ✨: Cấu hình thay đổi số tiền và pay_id trong json cấu hình ![](https://i.imgur.com/fUCJGJI.png) ![](https://i.imgur.com/XERlaL5.jpeg) ![](https://i.imgur.com/tmxnqEq.png)
- ☑: https://github.com/dh-hos/Du_An/issues/2 
## [v.3.24.1005.0]()
- ✨: **💼**: **_Dự án - Thanh toán QR - HD Bank_**
- ✨: Bổ sung thanh toán QR đối với 92013, 92086 sử dụng chuẩn VietQR ![](https://i.imgur.com/ev5jWgj.jpeg)
- ☑: https://github.com/dh-hos/Du_An/issues/2
## [v.3.24.1003.0]()
- 🐛: **💼**: **_Lỗi - BC Bảng kê chênh lệch cls dịch vụ load sai số lượng cls (BV Thanh Bình)_**
- 🐛:Chỉnh lỗi không đúng số lượng khi chọn link trên lưới Bảng kê chênh lệch CLS - Dịch vụ ![](https://i.imgur.com/B05Wlhy.png) ![](https://i.imgur.com/HcrJIF9.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/201 
## [v.3.24.1002.0]()
- 🐛: **💼**: **_Lỗi - Load thông tin bệnh nhân nội trú để thu tiền (BV Ô Môn)_**
- 🐛: Chỉnh lỗi khi chọn bệnh nhân ![](https://i.imgur.com/tTxRmpM.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/200
## [v.3.24.0930.0]()
- 🐛: **💼**: **_Lỗi - Chức năng Thu tự do không tìm kiếm được bệnh nhân (BV Phụ Sản)_**
- 🐛: Chỉnh lỗi không tìm kiếm được ![](https://i.imgur.com/ucwStGT.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/199
## [v.3.24.0921.0]()
- 🐛: **💼**: **_Lỗi - Fees thu tiền nhà thuốc toa bán lẽ bị âm tiền (BV Lấp Vò)_**
- 🐛: Chỉnh lỗi lấy sai số tiền (âm tiền) ![](https://i.imgur.com/NGswkHe.png) ![](https://i.imgur.com/C0Ek3Xm.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/197
## [v.3.24.0918.1]()
- ✨: **💼**: **_Yêu cầu - Bổ sung loại chi phí Không chịu thuế lên HĐĐT-Viettel_**
- ✨: Thêm chức năng cấu hình thuế suất với giá trị tùy chọn ![](https://i.imgur.com/B19dIVh.png)![](https://i.imgur.com/O6l0psK.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/195
## [v.3.24.0918.0]()
- 🐛: **💼**: **_Lỗi - Lập phiếu thu bệnh nhân báo lỗi (BV Tim Mạch CT)_**
- 🐛:Fix lỗi khi nhấn Thêm chứng từ ![](https://i.imgur.com/pVLBliR.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/196
## [v.3.24.0913.0]()
- ✨: **💼**: **_Yêu cầu - FEES - Triển khai thanh toán mã QR MOMO_**
- ✨: Thêm chức năng lưu cache QR theo qr_payId để tránh lập lại quá trình lấy QR nhiều lần, gây lỗi với hệ thống Momo ![](https://i.imgur.com/SkSwS2j.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/416
## [v.3.24.0911.0]()
- ✨: Hướng dẫn ẩn QRCODE khi không có QRData (chuỗi rỗng), mục đích người dùng không quét được khi QRData không hợp lệ
- ![](https://i.imgur.com/aAmpeQO.png) ![](https://i.imgur.com/i4Xc9w0.png)
- Script hỗ trợ ẩn QRCODE khi rỗng
```
// Sự kiện BeforePrint để kiểm tra và ẩn/hiển thị QRCode
private void HideIfEmpty_qrCodeControl_BeforePrint(object sender, System.Drawing.Printing.PrintEventArgs e)
{
    DevExpress.XtraReports.UI.XRBarCode qrCodeControl = sender as DevExpress.XtraReports.UI.XRBarCode
    // Kiểm tra nếu dữ liệu rỗng thì ẩn control
    if (string.IsNullOrEmpty(qrCodeControl.Text))
    {
        qrCodeControl.Visible = false; // Ẩn QRCode nếu không có dữ liệu
    }
    else
    {
        qrCodeControl.Visible = true; // Hiển thị QRCode nếu có dữ liệu
    }
}
```
- ✨: **💼**: **_Yêu cầu - FEES - Triển khai thanh toán mã QR MOMO_**
- ✨: Xử lý trả về chuỗi QRdata rỗng khi cấu hình không chính xác
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/416
## [v.3.24.0825.0]()
- ✨: Bổ sung trang thể hiện mã QR tự thiết kế (đăng nhập tài khoản admin sẽ hỏi trang thiết kế) đối với mã khách hàng không thuộc mẫu mặc định đã thiết kế riêng (**_92001,51214,70071,95006,92118_**)
![](https://i.imgur.com/13A5cXo.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/193
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/416
## [v.3.24.0824.1]()
- ✨: **💼**: **_Yêu cầu - Kiểm tra thông tin QR gửi cho Bank _**
- ✨: **💼**: **_Yêu cầu - FEES - Triển khai thanh toán mã QR MOMO_**
- ✨: Fix lỗi thiếu billNumber khi tạo QR khi in phiếu thu, tích hợp Momo, VietQR
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/193
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/416
## [v.3.24.0824.0]()
- ✨: **💼**: **_Yêu cầu - Kiểm tra thông tin QR gửi cho Bank _**
- ✨: Fix lỗi thiếu billNumber khi tạo QR khi in phiếu thu
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/193
## [v.3.24.0823.0]()
- ✨: **💼**: **_Yêu cầu - Kiểm tra thông tin QR gửi cho Bank _**
- ✨: Fix lỗi thiếu billNumber khi tạo QR
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/193
## [v.3.24.0821.2]()
- ✨: **Thực hiện**: **_Yêu cầu - BVĐK TPCT - Thực hiện thanh toán qua mã QR Viettinbank_**
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/265

## [v.3.24.0821.1]()
- ✨: Bổ sung XRptQRPayTTYTTPQuangNgai51014
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/264
## [v.3.24.0821.0]()
- ✨: **Thực hiện**: **_Yêu cầu - Phước Long BLI - Thực hiện thanh toán qua mã QR Viettinbank._**
- ✨: Thêm chức năng kiểm tra trạng thái thanh toán mã QR ![](https://i.imgur.com/ZXJiVH0.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/98
## [v.3.24.0820.0]()
- 🐛: **Chỉnh lỗi**: **_Yêu cầu - Phước Long BLI - Thực hiện thanh toán qua mã QR Viettinbank._**
- 🐛: Fix lỗi thiếu qrData trên phiếu tạm ứng ![](https://i.imgur.com/dt1WmIo.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/98
## [v.3.24.0817.1]()
- ✨: **Thực hiện**: **_Yêu cầu - Thanh toán QR Viettinbank tại BV Sản Nhi Trà Vinh_**
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/551

## [v.3.24.0817.0]()
- ✨: **Thực hiện**: **_Yêu cầu - Phước Long BLI - Thực hiện thanh toán qua mã QR Viettinbank._**
- ✨: Chỉnh sửa tiêu đề đối với màn hình thể hiện QRCode: ![](https://i.imgur.com/yAijRqe.png)
- ✨: Bổ sung para: qrData đối với phiếu tạm ứng (tamungtuin=1) ![](https://i.imgur.com/zS0ldY2.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/95
## [v.3.24.0813.1]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - PHÁT SINH LỖI KHI LẬP PHIẾU THU BỆNH NHÂN CÓ THUỐC NHÀ THUỐC_** ![](https://i.imgur.com/vtnY1MM.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/192
## [v.3.24.0813.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - PHÁT SINH LỖI KHI LẬP PHIẾU THU BỆNH NHÂN CÓ THUỐC NHÀ THUỐC_** ![](https://i.imgur.com/vtnY1MM.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/192

## [v.3.24.0803.0]()
- ✨: Yêu cầu - BV Phụ Sản: Yêu cầu bổ sung Tên đơn vị vào báo cáo Chi tiết chi phí nội bộ
- ![](https://i.imgur.com/2ZdUTcM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/563
## [v.3.24.0802.0]()
- ✨: Yêu cầu - BV Phụ Sản: Yêu cầu bổ sung Tên đơn vị vào báo cáo Chi tiết chi phí nội bộ
- ![](https://i.imgur.com/2ZdUTcM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/563
## [v.3.24.0801.0]()
- 🐛: Yêu cầu - Kiểm lỗi Fees trùng trong báo cáo Chi tiết theo dịch vụ
- ![](https://i.imgur.com/eg5ed2W.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/561
## [v.3.24.0704.0]()

- ✨: Yêu cầu thực hiện Theo mô tả - MÔ TẢ QUY TRÌNH TRẢ THUỐC/VTYT NGƯỜI BỆNH ĐIỀU TRỊ NỘI TRÚ
- Lấy thêm thông tin sohdx trên pshdxn để xử lý cấn trừ (lấy toàn bộ thông tin hóa đơn xuất, để áp cho hóa đơn trả, trừ số lượng và tiền)
- ![](https://i.imgur.com/gl8HMmF.png) ![](https://i.imgur.com/lGPu2tj.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/405
## [v.3.24.0626.0]()

- 🐛: Lỗi - Fees tính sai tiền cung chi trả đối với bệnh nhân đã có phiếu thu (BV Tâm Phúc)
![](https://i.imgur.com/SotusD3.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/188
## [v.3.24.0618.3]()
- ✨: DEVMODE
## [v.3.24.0612.0]()
- 🐛: Lỗi - Không thu được tiền đối với bệnh nhân có tổng có phát sinh cùng chi trả (trường hợp đã thu 1 phần)
![](https://i.imgur.com/9X2ifVD.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/174#issuecomment-2161981493
## [v.3.24.0611.0]()
- 🐛: Fix Lỗi - Không thu được tiền đối với bệnh nhân có tổng có phát sinh cùng chi trả (trường hợp đã thu 1 phần)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/174
## [v.3.24.0610.0]()
- ✨: Thực hiện chuyển phiếu Kết toán sang tự thiết kế (Yêu cầu - Đồng Tâm - Yêu cầu phiếu kết toán tại Fees chuyển khổ giấy A5)
![](https://i.imgur.com/BZ9vVlH.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/263
## [v.3.24.0607.1]()
- ✨: Test NAS
## [v.3.24.0607.0]()
- 🐛: Fix lỗi trường hợp thuốc trả và thuốc đánh toa khác chi phí miễn chi trả
- ![](https://i.imgur.com/MeBxYX1.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/163
- 📕: Xử lý kiểm tra nếu cphi_mienct của thuốc trả, không có trong thuốc đánh, thì xử lý giống thuốc đánh toa_
## [v.3.24.0606.0]()
- ✨: Kiểm tra nếu số thực thu nhỏ hơn 0, mà có bật tham số lapchungtu0dong = 1, sẽ gán lại giá trị 0
- 🐛: Lỗi - Không lập được phiếu thu 0 đồng (khi sử dụng tham số lapchungtu0dong = 1) bv lấp vò
- Do bệnh viện sử dụng chức năng tách hóa đơn, nên cũng phải tách 2 phần thành miễn giảm và thất thu để xử lý cho mỗi phiếu thu. Hướng dẫn video dưới đây.
- ![](https://i.imgur.com/oiWRBD6.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/178
## [v.3.24.0605.1]()
- ✨: Hỗ trợ kiểm tra Đã có phiếu thu sử dụng tiền tạm ứng của bệnh nhân thì không cho phép xóa phiếu này
- ![](https://i.imgur.com/OSbEZqV.png)
- 🐛: Hỗ trợ Lỗi Thu tiền nội trú thể hiện sai chi phí thu thêm 
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/140
## [v.3.24.0605.0]()
- 🐛: Fix lỗi không tính tiền lại khi xóa chi tiết CLS
- ![](https://i.imgur.com/XPMWjQ2.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/165
## [v.3.24.0602.1]()
- 🐛: Lỗi - Không hiển thị trang in đã được thiết kế.
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/179
## [v.3.24.0602.0]()
- 🐛: Lỗi - Nội dung thu bị trùng khi lập HDDT. (menu: Hóa đơn điện tử/Đồng bộ hóa đơn cuối ngày - Theo bệnh nhân)
- 🐛: Lỗi - Nút bỏ qua không có tác dụng
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/184
## [v.3.24.0601.2]()
- 🐛: Fix lỗi không tính lại thành tiền của phiếu thu
![](https://i.imgur.com/C86yIGH.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/165
## [v.3.24.0601.1]()
- 🐛: Xóa trạng thái selection row khi lấy lại dữ liệu mới
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/185
## [v.3.24.0601.0]()
- 🐛: Lỗi - Không chỉ định được những XN có chứa XN con
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/164
## [v.3.24.0531.1]()
- 🐛: Lỗi - Tính sai chi phí BN BANT thanh toán theo đợt có nhập giấy chứng nhận miễn (BV Ô Môn)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/170
## [v.3.24.0531.0]()
- 🐛: Kiểm tra trạng thái dữ liệu mới trước khi thực hiện lưu hoặc thêm nếu chưa nhấn lấy dữ liệu mới
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/166
## [v.3.24.0528.1]()
- ✨: Cập nhật Debug
## [v.3.24.0528.0]()
- 🐛: Fix xuống dòng địa chỉ trên phiếu thu
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/171
## [v.3.24.0527.1]()
- 🐛: Fix lỗi mất % lý do thu
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/183
## [v.3.24.0527.0]()
- 🐛: Fix lỗi mất % lý do thu
- 🐛: Fix xuống dòng địa chỉ trên phiếu thu
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/171
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/183
## [v.3.24.0525.0]()
- 🐛: Mở rộng text in địa chỉ trên phiếu thu
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/171
## [v.3.24.0524.0]()
- 🐛: Fix lỗi lập chi phí không phải nhà thuốc mà không cấn trừ tạm ứng
![](https://i.imgur.com/Bw6cVCm.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/358#issuecomment-2128329070
## [v.3.24.0523.0]()
- ✨: Fix lỗi không cấn trừ tạm ứng theo cấu hình
![](https://i.imgur.com/vLpGu7s.png)
![](https://i.imgur.com/QyoH8vf.png)
- 📕: Fix lỗi nút Thuốc NT không theo cấu hình
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/358
## [v.3.24.0522.0]()
- ✨: Thêm chức năng cho phép cấu hình sử dụng Cấn trừ tạm ứng khi thực hiện thu thuốc nhà thuốc (chức năng Thuốc NT trên form thu phí)
![](https://i.imgur.com/KpioPHQ.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/358
## [v.3.24.0521.1]()
- ✨: Bổ sung Logo đối với QRCode
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/95
## [v.3.24.0521.0]()
- ✨: Bổ sung Logo Vietin trên màn hình thể hiện QRCode
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/93
## [v.3.24.0520.0]()
- 📕: Xử lý gen QR theo thứ tự, nếu trong option coderun có sẽ lấy theo giá trị này, nếu rỗng sẽ lấy theo code cứng đã code trước
- 📕: Dữ liệu này sẽ được cập nhật từ cấu hình của webservices qrListener
## [v.3.24.0519.1]()
- ✨: Bổ sung QRCode BV Phước Long Bạc Liêu
- ☑: https://github.com/dh-hos/92001-qrcode-vietin
## [v.3.24.0519.0]()
- ✨: Bổ sung chức năng, khi màn hình có chiều cao từ 768 trở xuống sẽ rút gọn thông tin của bệnh nhân, và thêm chức năng [Mở rộng] để thể hiện những thông tin bị mất khi cần
![](https://i.imgur.com/OPshSmM.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/172
## [v.3.24.0518.0]()
- 🐛: Fix lỗi `Phiên bản :2024.05.18.151708PM
System.ArgumentException: Field must be specified in the group before adding it to the collection.
   at Janus.Data.JanusGroupCollectionBase.OnInsert(Int32 index, Object value)
   at Janus.Data.JanusCollectionBase.System.Collections.IList.Add(Object value)
   at Janus.Windows.GridEX.GridEXGroupCollection.Add(GridEXGroup group)
   at HosFees.ReportsV2.ReportForms.FrmBKThuChi.loadData()` 
![](https://i.imgur.com/6tM7xtY.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/162
## [v.3.24.0517.2]()
- 🐛: Fix lỗi khi chọn [Tạm ứng] ![image](https://i.imgur.com/309zyyK.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/182
## [v.3.24.0517.1]()
- 🐛: Fix lỗi lập phiếu thu khi có genQR, build lại để kiểm tra
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/181
## [v.3.24.0517.0]()
- 🐛: Fix lỗi lập phiếu thu khi có genQR, build lại để kiểm tra
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/181
## [v.3.24.0516.9]()
- 🐛: Fix Lỗi - Gen mã QR sai thông tin
- 🐛: Fix Lỗi - System.MissingMethodException: Method not found: 'Void OTH.PAY.ViettinBank.QRCode.ShowQR.ShowOnSecondScreenByQRPay  
![image](https://i.imgur.com/Z9DeYjy.png)
- ☑: https://github.com/dh-hos/dhg.hospitalfees/issues/181

##### [v3.23.1218.1]()

- 🐛: Lỗi bảng kê thu chi nội bộ (chi tiết) double chi phí (92118)

##### [v3.23.1208.1]()

- ✨: Bổ sung in chi tiết theo từng loại chi phí trên tab Chi tiết nội bộ (đây là mẫu tự thiết kế, đăng nhập bằng tài khoản admin để được phép thiết kế trang in này) ![Alt text](../MoTaThayDoi/HuongDan/BangKeBL-CPNoibo-0.png)
- ✨: Bổ sung cột tiền thanh toán không tiền mặt lên bảng kê biên lai nội bộ ![Alt text](../MoTaThayDoi/HuongDan/BangKeBL-CPNoibo-pay.png)

##### [v3.23.1201.1]()

- ✨: Thêm bảng kê chi tiết chi phí nội bộ theo CLS ![Alt text](../MoTaThayDoi/HuongDan/BangKeBL-CPNoibo.png)

##### [v3.23.1130.2]()

- 🐛: Chọn loại biên lai mặc định khi thêm chứng từ
- 🐛: Lỗi cảnh báo phiếu thu nội bộ không phù hợp (92118)

##### [v3.23.1130.1]()

- 🐛: Lỗi cảnh báo phiếu thu nội bộ không phù hợp (92118)

##### [v3.23.1020.1]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/57>
- 🐛: Yêu cầu - Lập hóa đơn điện tử chi tiết tại form Thu CLS tự do trên Fees

##### [v3.23.1016.4]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/126>
- ✨: Yêu cầu - Cấp license thêm mã đơn vị triển khai mới - BV Đa Khoa Tâm Minh Đức Tiền Giang

##### [v3.23.1016.3]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/126>
- ✨: Yêu cầu - Cấp license thêm mã đơn vị triển khai mới - BV Đa Khoa Tâm Minh Đức Tiền Giang

##### [v3.23.1016.2]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/126>
- ✨: Yêu cầu - Cấp license thêm mã đơn vị triển khai mới - BV Đa Khoa Tâm Minh Đức Tiền Giang 

##### [v3.23.1016.1]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/126>
- ✨: Yêu cầu - Cấp license thêm mã đơn vị triển khai mới - BV Đa Khoa Tâm Minh Đức Tiền Giang

##### [v3.23.0928.1]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/57>
- ✨: Thêm chức năng cho phép lập hóa đơn điện tử với chi tiết chi phí (nhiều dòng hàng hóa) không theo cấu hình tham số.![Alt text](../MoTaThayDoi/HuongDan/Hddt-ChiTiet-ChiPhi.png)
- ✨: Thực hiện: Yêu cầu - Lập hóa đơn điện tử chi tiết tại form Thu CLS tự do trên Fees.

##### [v3.23.0925.2]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/82>
- ✨: Thực hiện: Yêu cầu - Encode nội dung xóa hóa đơn Viettel. Bổ sung UrlEncode lý do khi thực hiện xóa hddt trên hệ thống Viettel.

##### [v3.23.0915.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/139>
- 🐛: Fix Lỗi - Đồng Tâm - Báo cáo viện phí > Chi tiết theo dịch vụ > tiền thuốc x2

##### [v3.23.0911.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/100>
- 🐛: Fix Lỗi - BV Sa Đéc: Thu phí 1đ bệnh nhân có chi phí nguồn khác

##### [v3.23.0910.3]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/127>
- 🐛: Fix Lỗi - Sai giới tính báo cáo tổng hợp - Viện phí thu tiền dịch vụ

##### [v3.23.0910.2]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/129>
- 🐛: Fix xóa hóa đơn tổng không xóa được chi tiết. Hướng xử lý kiểm tra nếu không có phiếu thu thì cảnh báo lấy lại dữ liệu trước khi xóa.

##### [v3.23.0910.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/130>
- 🐛: Fix tính sai chi stent2 đối với đối tượng thu phí trên bảng kê chi tiết và tổng hợp theo bệnh nhân

##### [v3.23.0908.1]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/67> 
- ✨: Điều chỉnh VATRateName = "KCT" đối với hóa đơn giá trị gia tăng hông có thuế
- ✨: Bổ sung chức năng đưa thông tin thuế suất khi đưa hddt MISA![Alt text](../MoTaThayDoi/HuongDan/Hddt-Misa-ThueSuat-01.png)![Alt text](../MoTaThayDoi/HuongDan/Hddt-Misa-ThueSuat-02.png)

##### [v3.23.0906.1]()

- #️⃣: <https://github.com/dh-hos/To_Lap_Trinh/issues/67>
- ✨: Bổ sung chức năng đưa thông tin thuế suất khi đưa hddt MISA![Alt text](../MoTaThayDoi/HuongDan/Hddt-Misa-ThueSuat-01.png)![Alt text](../MoTaThayDoi/HuongDan/Hddt-Misa-ThueSuat-02.png)

##### [v3.23.0824.1]()

- ✨: Bổ sung thanh toán Thẻ VietinBank (84006)

##### [v3.23.0817.1]()

- 🐛: Fix lỗi Bảng kê thu chi đối với phiếu thu nhà thuốc đối với bệnh viện Tim Mạch CT (92001)

##### [v3.23.0814.1]()

- 🐛: Fix lỗi bảng kê biên lai đối với phiếu thu nhà thuốc đối với bệnh viện Tim Mạch CT (92001) 

##### [v3.23.0810.1]()

- ✨: Bổ sung chức năng thanh toán QRCode đối với bệnh viện Tim Mạch CT (92001)

##### [v3.23.0807.2]()

- ✨: Thêm chức năng ký số thông qua USB khi kết nối Hddt MISA (Mỗi máy con phải có usb ký số kết nối trực tiếp khi lập hóa đơn) ![Alt text](../MoTaThayDoi/HuongDan/Hddt-Misa-KySoUSB.png)

##### [v3.23.0807.1]()

- ✨: Thêm chức năng ký số thông qua USB khi kết nối Hddt MISA (Mỗi máy con phải có usb ký số kết nối trực tiếp khi lập hóa đơn) ![Alt text](../MoTaThayDoi/HuongDan/Hddt-Misa-KySoUSB.png)

##### [v3.23.0623.1]()

- #️⃣: <https://github.com/dh-hos/Mo-ta-he-thong/issues/25>
- ✨: Cập nhật Lisence `92117`

##### [v3.23.0621.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitaladmin/issues/43>
- ✨: Cập nhật Lisence `77155`

##### [v3.23.0606.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitaladmin/issues/42#issuecomment-1578201157>
- ✨: Cập nhật Lisence `77156`

##### [v3.23.0531.1]()

- ✨: Cập nhật chức năng tính tiền dịch vụ và tiền thường khi có miễn giảm, hiện tại toàn bộ miễn giảm sẽ cấn trừ vào tiền thường, fix lại nếu tiền thường nhỏ hơn tiền miễn giảm sẽ cấn trừ thêm qua phần dịch vụ. 

##### [v3.23.0504.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/123>
- 🐛: Fix lỗi: Không in phiếu thu tự thiết kế.

##### [v3.23.0418.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/122>
- 🐛: Fix lỗi: Không in hoàn ứng được.

##### [v3.23.0412.2]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/121>
- 🐛: Fix lỗi: BC Bảng kê chi tiết theo bệnh nhân (Tổng hợp & nội trú) lệch tiền so với phiếu thu

##### [v3.23.0412.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hosptaltreatment/issues/65>
- #️⃣: <https://github.com/dh-hos/Mo-ta-he-thong/issues/22>
- ✨: Thực hiện - Ghi nhận MỨC HƯỞNG chi phí BHYT của người bệnh khi áp NGÀY MIỄN CÙNG CHI TRẢ theo thẻ BHYT và áp dụng cách tính khi có ngày kết thúc miễn chi trả.

##### [v3.23.0410.3]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/114>
- 🐛: Fix lỗi: Tạo HDDT cho phiếu thu đã xóa. Thực hiện kiểm tra những phiếu thu đã xóa sẽ không đồng bộ HĐĐT.

##### [v3.23.0410.2]()

- 🐛: Fix lỗi: Ghi nợ bệnh nhân có BANT theo đợt

##### [v3.23.0410.1]()

- #️⃣: <https://github.com/dh-hos/dhg.hospitalfees/issues/119>
- ✨: Thêm hình thức thanh toán trên bảng kê biên lai (để hỗ trợ lọc theo httt)

##### [v3.23.0308.3]()

-  âœ¨:
-  ðŸ›:
-  #ï¸âƒ£:

##### [v3.23.0308.2]()

-  âœ¨:
-  ðŸ›:
-  #ï¸âƒ£:

##### [v3.23.0308.1]()

-  âœ¨:
-  ðŸ›:
-  #ï¸âƒ£:

##### [v3.23.0109.2]()

-  âœ¨:
-  ðŸ›:
-  #ï¸âƒ£:

##### [v3.23.0109.1]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitaladmin/issues/27
-  ✨: Cập nhật bản quyền đối với Mã BV 87192; 87196

##### [v3.22.1226.1]()

-  #️⃣: https://github.com/dh-hos/Mo-ta-he-thong/issues/21
-  #️⃣: https://github.com/dh-hos/dhg.hospitaladmin/issues/25
-  ✨: Cập nhật bản quyền đối với Mã BV 92137; 77154

##### [v3.22.1202.1]()

-  🐛: Cấn trừ tiền tạm ứng khi thanh toán bằng máy POS
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/105

##### [v3.22.1201.3]()

-  ✨: Bổ sung control cho phép nhập hình thức thanh toán trên Form tạm ứng, và bảng kê tạm ứng thể hiện thêm cột hình thức thanh toán ![Alt text](../MoTaThayDoi/HuongDan/TamUng-HTTT-0.png) ![Alt text](../MoTaThayDoi/HuongDan/TamUng-HTTT-1.png)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/104

##### [v3.22.1201.2]()

-  ✨: Bổ sung cột thể hiện số tiền thanh toán qua POS trên bảng kê thu chi - tab Tổng hợp ![Alt text](../MoTaThayDoi/HuongDan/BangKeThuChi-TabTonghop-ThanhtoanPay.png)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/103

##### [v3.22.1201.1]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/102
-  🐛: Thể hiện số tiền tạm ứng ra tivi để thanh toán QR
-  🐛: Thể hiện đúng số tiền tạm ứng còn lại khi thể hiện QR ra tivi
-  ✨: Bổ sung nút in tự thiết kế trên form phiếu chi ![Alt text](../MoTaThayDoi/HuongDan/PhieuChi-InTuThietKe.png)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/101

##### [v3.22.1110.1]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/95
-  ✨: Hỗ trợ xử lý index đối với HĐĐT VAT (trong chi tiết hóa đơn)

##### [v3.22.1103.1]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/90
-  ✨: Bổ sung thêm tab Chi tiết theo biên lai - Lao Phổi ĐT đặc thù đối với mabvbh=87115, phần CPVC chưa đưa lên sẽ thấy theo kho CV, CV2, VTYT, lấy theo kho 03, Máu lấy theo kho 02, Oxy lấy theo Kho thuốc 01 và thuộc manhom=30, phần còn lại đưa tất cả vào thuốc (điều kiện kho chính là dmthuoc.kho).![Alt text](../MoTaThayDoi/HuongDan/BangKe-ChitietTheoBN-87115.png)

##### [v3.22.1029.4]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/82
-  🐛: Fix lỗi thể hiện check Loại Khách hàng (Công ty,D.nghiệp) trên phiếu thu tự do

##### [v3.22.1029.3]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/83
-  🐛: Fix lỗi không gửi dongia, soluong, dvt đối với trường hợp phiếu thu tự do khi gửi hddt (VAT)

##### [v3.22.1029.2]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/84
-  🐛: Nguyên nhân âm tiền do ảnh hưởng của xử lý cận lâm sàng thuộc ktcao => Bỏ xử lý theo ktcao trong bảng chidinhcls (Đã không còn phù hợp)

##### [v3.22.1029.1]()

-  ✨: ![](../MoTaThayDoi/HuongDan/Hddt-Ghi-nhat-ky-cau-hinh.png)
-  ✨: Nội dung thay đổi theo dạng json:
-  ✨: Bổ sung chức năng ghi nhật ký khi chỉnh thông tin cấu hình hóa đơn điện tử (tác vụ: Chỉnh cấu hình hóa đơn điện tử - HĐĐT) khi có thay đổi trên form cấu hình
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/86

##### [v3.22.1028.2]()

-  🐛: Fix chức năng đồng bộ hóa đơn điện tử cuối ngày theo cấu hình riêng cho nhà thuốc
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/87

##### [v3.22.1028.1]()

-  ✨: Bổ sung thêm chức năng lấy lại thông tin hóa đơn đã lập dựa vào Ikey với HDDT Softdream. Nếu lập lỗi, sẽ kiểm tra nếu Ikey đã tồn tại trên hệ thống thì lấy thông tin hóa đơn để cập nhật vào hệ thống.![](../MoTaThayDoi/HuongDan/Hddt-Softdream-LayLaiThongtinHoaDon-TheoIKey.png)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/88
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/85

##### [v3.22.1026.1]()

-  ✨: Bổ sung báo cáo thu tiền qua POS ![](../MoTaThayDoi/PAYs/POS-UNGBUOU-SACOMBANK/pay-pos-ungbuou-cauhinhhis-05.png)![](../MoTaThayDoi/PAYs/POS-UNGBUOU-SACOMBANK/pay-pos-ungbuou-cauhinhhis-06.png)![](../MoTaThayDoi/PAYs/POS-UNGBUOU-SACOMBANK/pay-pos-ungbuou-cauhinhhis-07.png)

##### [v3.22.1025.1]()

-  ✨: Bổ sung hình thức thanh toán trên Bảng kê biên lai đối với mã bệnh viện: `92086` - Ung Bướu Cần Thơ ![](../MoTaThayDoi/HuongDan/BangKeBL-ThemHinhThucThanhToan.png)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/89

##### [v3.22.1024.1]()

-  ✨: Bổ sung hình thức thanh toán trên Bảng kê biên lai đối với mã bệnh viện: `92086` - Ung Bướu Cần Thơ
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/89

##### [v3.22.1018.1]()

-  ✨: Thêm chức năng chọn chứng từ thể hiện QR-Code ra màn hình thứ 2 được kết nối với máy tính hiện tại

##### [v3.22.1012.1]()

-  ✨: [Hướng dẫn triển khai](../MoTaThayDoi/PAYs/POS-UNGBUOU-SACOMBANK/huong-dan.md)
-  ✨: Thêm chức năng kết nối thanh toán bằng máy POS Ung Bướu (Sacombank) [](<../MoTaThayDoi/PAYs/POS-UNGBUOU-SACOMBANK/INGENICO_ECR%20(Web_COM%20RS232)%20Generic%20Guide_V203_05Mar2018.pdf>)

##### [v3.22.1011.1]()

-  ✨: Thêm chức năng kết nối thanh toán bằng máy POS Ung Bướu (Sacombank)

##### [v3.22.0929.7]()

-  🐛: Fix lỗi thiếu thông tin phiếu thu khi sử dụng quét mã vạch tìm tên bệnh nhân và tự động in phiếu thu
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/72

##### [v3.22.0929.6]()

-  🐛: Fix lỗi thể hiện sai chi phí bệnh nhân khi chọn danh sách trên lưới bệnh nhân.
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/75

##### [v3.22.0929.5]()

-  ✨: Thêm chức năng cấu hình cho phép bắt buộc nhập Quyển và ký hiệu trên form Tạm ứng, hoàn ứng (Menu->Tiện ích->Cấu hình tham số) ![](../MoTaThayDoi/HuongDan/Fees-Option_quyenKyhieu-TU-HU.png)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/80

##### [v3.22.0929.4]()

-  🐛: Fix Bảng kê miễn giảm ngoại trú không lấy được dữ liệu
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/76

##### [v3.22.0929.3]()

-  🐛: Fix Thể hiện nhóm chi phí lại trên lưới CLS và thuốc (hạn chế cùng mã CLS hoặc thuốc, nhưng có thể chọn thu hay không trên phiếu thu). Lưu ý, những phiếu thu đã sai, phải xóa lập lại thì mới đúng chi phí lại.
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/69

##### [v3.22.0929.2]()

-  🐛: Fix Thao tác chỉnh phiếu thu phần chênh lệch BHYT (sau khi chỉnh không thể tính đúng % đồng chi trả toàn bộ chi phí bệnh nhân)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/68

##### [v3.22.0929.1]()

-  🐛: Fix lỗi Bảng kê tổng hợp theo dịch vụ load sai chi phí đối với chi phí thuộc Miễn chi trả và stent2
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/62

##### [v3.22.0928.1]()

-  ✨: Cập nhật bản quyền đối với Mã BV 87190 - BỆNH VIỆN DA LIỄU ĐỒNG THÁP
-  #️⃣: https://github.com/dh-hos/DH.HIS/issues/4

##### [v3.22.0922.14]()

-  ✨: Thay đổi mã kết nối với QRCode - Viettinbank

##### [v3.22.0922.13]()

-  ✨: Hỗ trợ thanh toán bằng QRCode - Viettinbank

##### [v3.22.0922.12]()

-  ✨: Hỗ trợ thanh toán bằng QRCode - Viettinbank

##### [v3.22.0922.6]()

-  ✨: Hỗ trợ thanh toán bằng QRCode - Viettinbank

##### [v3.22.0922.5]()

-  ✨: Hỗ trợ thanh toán bằng QRCode - Viettinbank

##### [v3.22.0922.4]()

-  âœ¨:
-  ðŸ›:
-  #ï¸âƒ£:

##### [v3.22.0922.3]()

-  âœ¨:
-  ðŸ›:
-  #ï¸âƒ£:

##### [v3.22.0922.2]()

-  ✨: Hỗ trợ thanh toán bằng QRCode - Viettinbank

##### [v3.22.0915.1]()

-  ✨: Bổ sung chức năng xóa hóa đơn điện tử đã thực hiện download từ cổng về (lần in hóa đơn kế tiếp sẽ download trực tiếp trên cổng lại)

##### [v3.22.0721.2]()

-  🐛: Fix lỗi xác định sai chi phí nhà thuốc đối với trường hợp bán lẻ (kho cấp phát không thuộc kho Nhà thuốc, nhưng vẫn ghi nhận chi phí nhà thuốc) [Những phiếu thu nào đã ghi nhận sai chi phí, muốn đúng phải xóa lập lại mới đúng chi phí lại]
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/59

##### [v3.22.0721.1]()

-  🐛: Bổ sung license mabvbh=77150
-  #️⃣: https://github.com/dh-hos/DH.HIS/issues/2

##### [v3.22.0720.1]()

-  🐛: Fix trường hợp lập phiếu thu không theo tham số phieuthubnchuaxv
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/55#issuecomment-1189693317

##### [v3.22.0719.2]()

-  🐛: Fees không tính được tiền của stent thứ 2 có số lượng lớn
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/58
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/55

##### [v3.22.0719.1]()

-  🐛: Fix Bảng kê biên lai thể hiện âm chi phí viện phí khi có chi phí thuộc nhà thuốc
-  ✨: Đổi tiêu đề trên bảng kê biên lai [Dịch vụ (viện phí)] => [Chi phí (viện phí)],[Dịch vụ (nhà thuốc)] => [Chi phí (nhà thuốc)]
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/57

##### [v3.22.0708.1]()

-  ✨: Áp dụng thêm tham số `vpnhathuoc`,`vpnhathuoc_khocp` đối với đối tượng BHYT và Trẻ em (lấy toàn bộ thông tin thuốc thuộc BHYT và thuốc Nhà thuốc theo cấu hình `vpnhathuoc_khocp`)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/54

##### [v3.22.0707.1]()

-  ✨: Mở chức năng Viện phí dành riêng cho nhà thuốc đối với BV Nhi Đồng (TP Cần Thơ - 92003)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/51

##### [v3.22.0706.1]()

-  🐛: In phiếu thu trên lưới chứng từ thu chi thiếu matracuu_hddt
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/53

##### [v3.22.0629.5]()

-  ✨: Bổ sung lý do khi xóa hddt của Viettel vào trường `reasonDelete`
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/52

##### [v3.22.0629.4]()

-  ✨: Yêu cầu trong nhật ký gửi Hóa đơn điện tử của VAT bổ sung thêm thời gian bắt đầu và kết thúc khi Lập hóa đơn điện tử.
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/50

##### [v3.22.0629.3]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/47
-  ✨: Bổ sung thêm chổ thu tự do cho nhập đầy đủ Đơn vị tính, đơn giá, số lượng, thành tiền. (Kết nối với Hddt: `VAT, VNPT`, `VIETTEL`, `MISA`, `EASYINVOICE`). Ghi chú: `Khi điều kiện để đưa thông tin số lượng, đơn giá lên cổng hóa đơn là: là phiếu thu tự do (loai='pttd') có đơn vị tính, số lượng và đơn giá lớn hơn 0.`

##### [v3.22.0629.2]()

-  #️⃣: Truyền thêm thông tin số tài khoản (phiếu thu) khi lập hóa đơn điện tử của VNPT. (đổi `ComBankNo` sang `CusBankNo`)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/46

##### [v3.22.0629.1]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/49
-  🐛: Bảng kê bệnh nhân nợ viện phí cũng hiển thị bệnh nhân còn nợ
-  🐛: Bệnh nhân có stent 2 đã thu hết chi phí nhưng bảng kết toán viện phí vẫn ghi nhận bệnh nhân còn nợ.
-  🐛: Fix Không đủ chổ trống ghi nhận số tiền trên bảng kết toán viện phí nên hiển thị số tiền ########

##### [v3.22.0623.1]()

-  ✨: Bổ sung theo dõi nội dung cập nhật module Fees [tại đây](https://github.com/dh-hos/dhg.hospitalfees/blob/main/Deploy_Tools/CHANGELOG.md)

