pallet-kitties
Calls
create
Storages
Kitties: double_map AccountId, u32 => Option<Kitty>
NextKittyId: u32
Types
struct Kitty([u8; 16])
Events
KittyCreated
owner: AccountId
kitty_id: u32
kitty: Kitty