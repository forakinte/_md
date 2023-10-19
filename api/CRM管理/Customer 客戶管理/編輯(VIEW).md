# CPKG-110000-Fuji

## CRM管理 > 客戶管理 API

### 此項目權限依附於 fuji/customer-manager/lists

> 編輯(view)

| 項目                      | 內容                       | 說明                |驗證                      |   備註         |
|---------------------------|----------------------------|----------------------|-----------------|----------------|
| <b>路徑</b>               | fuji/customer-manager/modify    |                        |                |                  |
| <b>方法</b>               | GET                        |                    |                    |                 |
| <b>權限</b>               | 檢視                       |                     |                   |                 |
| <b>參數</b>               |                            |                       |                 |                 |
|                          | cp11_com_id             | ID            | 必填,整數               |                 |

> 回傳

| 參數                                                                        | 說明                            | 備註                           |
|----------------------------------------------------------------------------|--------------------------------|--------------------------------|
| cp11_com_id               | ID                            |                                |
| cp11_com_customer_code               | 客戶代碼                            |                                |
| cp11_com_customer_name               | 客戶名稱                            |                                |
| cp11_com_tax_id             | 統編                            |                                |
| cp11_com_address_area             | 地區                            |                                |
| cp11_com_address_dist             | 行政區                            |                                |
| cp11_com_address             | 地址                            |                                |
| cp11_com_dean_name             | 院長名稱                            |                                |
| cp11_com_principal_name             | 負責人名稱                            |                                |
| cp11_com_principal_phone             | 負責人電話                            |                                |
| cp11_com_contact_name             | 聯絡人名稱                            |                                |
| cp11_com_contact_phone             | 聯絡人電話                            |                                |
| cp11_com_line_id             | 客戶LINE ID                            |                                |
| cp11_com_email             | 客戶email                            |                                |
| cp11_com_phone             | 客戶電話                            |                                |
| cp11_com_fax             | 客戶傳真                            |                                |
| cp11_com_memo             | 備註                            |                                |
| selfDevice             | 設備                            |                                |
| selfDevice[][cp11_cde_id]             | 設備ID                            |                                |
| selfDevice[][cp11_cde_brand_name]             | 設備品牌                            |                                |
| selfDevice[][cp11_cde_pattern_name]             | 設備型號                            |                                |
| selfDevice[][cp11_cde_serial_number]             | 設備序號                            |                                |
| selfDevice[][cp11_cde_contract_date]             | 簽約日                            | yyyy-mm-dd                               |
| selfDevice[][cp11_cde_install_date]             | 裝機日                            | yyyy-mm-dd                               |
| selfDevice[][cp11_cde_expire_date]             | 到期日                            | yyyy-mm-dd                               |
