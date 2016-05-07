Docs=<h3>Seed Round</h3><br><b>Term Sheet</b><br>{TermSheet.Doc}<hr><b>Investment Agreement</b><br>{Invest.Doc}<hr><b>Certificate of Incorporation</b><br>{Incorp.Doc}

Company.PreMoney.Value.$=500,000 Euros

Investor.All.Investment.Amount=Seventy Thousand Euros

MajorInvestorThreshold.$=20,000 Euros

Investor.Attorney.Reimburse.$=10,000 Euros

Company.Cap.Option.Unallocated.%=20%

For Investment Agreement=:

Company.Cap.Plan.Name=Acme Employee Stock Option Plan

PricePerShare.$=Two Euros

Company.Cap.Common.Outstanding.PreMoney.#=200,000

Company.Cap.Option.Reserve.#=50,000

Company.Cap.Option.Outstanding.#="0"

Company.Cap.Option.Unallocated.#=50,000

Investor.1.=[Dx/Acme_FR/14-Galion-Series-A/Seed_Round/Investor_1_v0.md]

Investor.2.=[Dx/Acme_FR/14-Galion-Series-A/Seed_Round/Investor_2_v0.md]

Company.Director.Common.#=two directors

Company.Director.Seed.#=1 director

Company.Director.Mutual.#=1 director

KeyHolder.Vest.Begin=January 1, 2018

Company.Register.State=France 


Cerfificate of Incorporation=-

Company.Cap.All.Auth.Max.#=100,000,000

Company.Cap.Common.Auth.#=20,000,000

Company.Cap.Common.Par.$=$0.01 

Company.Cap.Seed.Auth.#=10,000,000

Company.Cap.Seed.Par.$=$0.01

Document Mechanics=-

Investor-N.Row={Investor.1.Row}{Investor.2.Row}

Investor.Sign.Block=<table><tr><td>{Investor.1.Sign.Block}</td><td>{Investor.2.Sign.Block}</td></tr></table>

TermSheet.Effective.YMD=January 16, 2016

Invest.EffectiveDate.YMD=April 6, 2016

Invest.DisputeResolutionJurisdiction.cl={DisputeResolutionJurisdiction.cl}

Model.Root={Docs}

=[Wx/com/seriesseed/Binder_v0.md]